# Radiometric Terrain Correction for Sentinel-1 in Vertex

The Alaska Satellite Facility now offers Radiometric Terrain Correction of Sentinel-1 scenes through ASF Data Search - Vertex.  You can now submit scenes to be processed into normalized radar backscatter products on your behalf, avoiding the cost and complexity of performing such processing yourself.

SAR datasets inherently contain geometric and radiometric distortions due to terrain being imaged by a side-looking instrument. Radiometric terrain correction (RTC) removes these distortions and creates analysis-ready data suitable for use in GIS applications. RTC processing is a required first step for many amplitude-based SAR applications.

Sentinel-1 RTC products are generated by ASF's HyP3 processing platform leveraging GAMMA Software.  Products are distributed as UTM-projected GeoTIFFs with a pixel spacing of 30 meters. To learn more, visit the [ASF Sentinel-1 RTC Product Guide](https://asf.alaska.edu/wp-content/uploads/2019/02/Sentinel_RTC_Users_Guide.pdf).

## Getting Started

To request RTC products, visit [ASF Data Search - Vertex](https://search.asf.alaska.edu).

1. **Select your scenes** - RTC processing is available for Sentinel-1 GRD-H and SLC scenes with a beam mode of IW. When searching for Sentinel-1 scenes, an *Add RTC to On Demand queue* <img width="25" src="https://avatars1.githubusercontent.com/u/68247451" /> option appears for these files.

1. **Submit your request** - After selecting your scenes, access the  *On Demand* <img width="30" src="https://user-images.githubusercontent.com/17994518/95892024-588b9280-0d32-11eb-8734-f1a54a9d2a20.png" /> queue to submit your processing request. You may process up to 200 scenes per month.

1. **Monitor your request** - The new *On Demand Products* search type displays your running and completed requests. New requests typically require 20-60 minutes before a finished RTC product is available.

1. **Download your data** - Finished RTC products can be downloaded after an *On Demand Products* search either directly <img width="25" src="https://user-images.githubusercontent.com/17994518/95271858-6ea5ca00-07eb-11eb-9217-a280ca57a5e6.png" /> or via your download queue <img width="25" src="https://user-images.githubusercontent.com/17994518/95271856-6d749d00-07eb-11eb-81d8-365a6221e4f1.png" />. On Demand products are retained and available to download for two weeks after processing.

## Feedback

ASF would love to hear from you! Let us know what you liked, didn't like, or what we can do better.

* For data search and general feedback, [open a support ticket](https://fbm.earthdata.nasa.gov/tickets/new?app_name=ASF&token=%242a%2412%24t0ZIDodY843bRbaRWUZ2QuCHt3JYlCRsfEhh6RY9DMCSjEAl0S96e) or [email ASF User Services](mailto:uso@asf.alaska.edu).

* For RTC product and custom processing feedback, [chat with us on gitter](https://gitter.im/ASFHyP3/community) or [open an issue](https://github.com/ASFHyP3/ASFHyP3/issues/new).

* Not sure which? [Email ASF User Services](mailto:uso@asf.alaska.edu).