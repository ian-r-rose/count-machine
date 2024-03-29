# Great Streets + Department of Transportation + Information Technology Agency - Count Machine

## About

The City currently does bicycle and pedestrian counts via having a person manually the number of cyclists and pedestrians that go through an intersection via a video capture. 

However, thanks to advances in Machine Vision technology, we could now automate that, allowing us to constantly count the number of pedestrians and cyclists, rather than only doing a 24 hour sample. 

This project is a proof of concept of how we could count the number folks moving through our streets. 
## Sponsors

Jeanne Holm, ITA

Great Streets - WHO? 

DOT - Seleta Reynolds, Marcel Porras 

## Partners

CSU LA, Dr. Mohammad Pourhomayoun
## City Team

Hunter Owens

## Goals

Long term, allow us to know annual active transportation counts for key corridors. 

## Deliverables

Using the Google Machine Vision API or similar algorithm, take data from video feeds and produce bicycle and pedestrian counts in the same format we got before. 

## Data Sources

* Video Data (see s3://traffic-video-lacity/). To download the video data, install the [AWS Command Line Tools](https://aws.amazon.com/cli/) and run `aws s3 cp --recursive s3://traffic-video-lacity/ /local/path/for/data`.
* Count Ouput data (see `data` directory)
