# acousticfeatures-fhs
Script to extract acoustic features

### Overview
This repo contains files to extract acoustic features.

1. You will need to install the OpenSmile toolkit: http://audeering.com/technology/opensmile/

The command to generate the features is:
`SMILExtract -C config/myIS13_ComParE_8K.conf -I sample_8K.wav`

This results in **output.lld.csv** (low-level-descriptors, ie. frame-level features) and **smile.log** being generated, according to the configuration defined in **config/myIS13_ComParE_8K.conf**. You can use other provided configurations as you like.

**sample_8K.wav** is the classic TIMIT phrase: _"She had your dark suit in greasy wash water all year"_

_Last Updated 11th September 2017_
