#!/usr/bin/env groovy
// vim: set ts=4 sts=4 sw=4 et:

// Items to synchronize into bucket
String[] items = [
    'index.html',
    'about/',
    'asteroid/',
    'education/',
    'static/',
    'timelapse/',
]

// Standard LCO AWS S3 Bucket synchronization pipeline
s3BucketPipeline([
    awsCredentials: 'jenkins-publish-asteroidtracker.lco.global',
    s3Bucket: 'asteroidtracker.lco.global',
    items: items,
])
