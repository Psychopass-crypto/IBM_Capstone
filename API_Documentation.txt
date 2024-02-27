                           API DOCUMENTATION:



Make sure that you run the server with python3 app.py or python3 app.py -d

  Request type    | Key            | Description
 =======================================================================
  /train          | mode           | Training mode - test or prod
 -----------------+----------------+------------------------------------
                  | query          | Query for model, must be a dict containing 
  /predict        |                | 'country','year','month','day' as keys, with their
                  |                | values as strings.
                  | mode           | Model to be used - test or prod
 -----------------+----------------+------------------------------------
  /logs           | filename       | Name of log file to retrive
 -----------------+----------------+------------------------------------
