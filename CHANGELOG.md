
## 2017-03-10

  * Dark Vision now processes audio from videos too. It uses Watson Speech to Text to extract the audio track. Then the audio is processed by Natural Language Understanding to extract concepts, entities, emotion.

  * New visual design for the web interface.

## 2017-02-15

  * A new toolchain to deploy Dark Vision in two steps! Head over to the README for details.

## 2017-01-11

  * No more *deploy-darkvision.sh*. It has been replaced by **deploy.js** in the root folder. The goal is to support deployment of the actions from Windows too. It was a bit too challenging to maintain shell scripts and Windows commands so instead Dark Vision relies on a node script. Node.js version 6.7.0 minimum is required.

  * The *local.env* file has changed location too. It is now in the root directory.
