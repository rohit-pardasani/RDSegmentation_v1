# RDSegmentation_v1
  Quantitative Assessment of RD using segmentation of multi-variate time series 
Respiratory  Distress  (RD)  is  typically  associated  withmany critical conditions, particularly in aged population.The  present-day  monitoring  solutions  do  not  track  theseverity of RD distinctly and this obscures accurate prog-nosis.  Our method quantifies RD condition to a ‘SeverityIndex (SI)’ in a real time monitoring setup. We achieve this by tracking pattern of respiratory rate (RR), oxygen saturation (SpO2) and heart rate (HR) over time using Convolutional Neural Network (CNN) based model for multivariate time series segmentation.   The CNN based approachis then compared with other two different approaches viz.Long-Short  Term  Memory  (LSTM)  model  and  Bayesian Inference  model  based  on  Symbolic  Aggregate  approXi-mation  (SAX).  We  work  on  segments  extracted  from  180records  of  MIMIC-III  Clinical  and  Waveform  Database,after getting them clinically annotated.  Our CNN, LSTMand SAX models achieve RMSE (Root Mean Square Error)of 0.288, 0.301 and 0.305 respectively with respect to theclinical annotations.  All methods achieve AUC (Area Un-der  Curve  for  Receiver  Operating  Characteristic(ROC))close to 0.95
