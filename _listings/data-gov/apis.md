---
name: Data.Gov
x-slug: data-gov
description: data.gov is a U.S. government website launched in late May 2009 by the
  then Federal Chief Information Officer (CIO) of the United States, Vivek Kundra.
  According to its website, The purpose of data.gov is to increase public access to
  high value, machine readable datasets generated by the Executive Branch of the Federal
  Government. The site seeks to become a repository for all the information the government
  collects. The site would publish to the public any data that is not private or restricted
  for national security reasons.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Data
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/apis.md
specificationVersion: "0.14"
apis:
- name: Data.gov API Get Datasets
  x-api-slug: data-gov-api
  description: List or search all datasets
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/
  tags: Datasets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasets-get-openapi.md
- name: Data.gov API Add Datasets
  x-api-slug: data-gov-api
  description: Create a new dataset
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/
  tags: Datasets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasets-post-openapi.md
- name: Data.gov API Get Datasets Badges
  x-api-slug: data-gov-api
  description: List all available dataset badges and their labels
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/badges/
  tags: Datasets, Badges
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsbadges-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsbadges-get-openapi.md
- name: Data.gov API Get Datasets Checkurl
  x-api-slug: data-gov-api
  description: Checks that a URL exists and returns metadata
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/checkurl/
  tags: Datasets, Checkurl
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetscheckurl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetscheckurl-get-openapi.md
- name: Data.gov API Get Datasets Community Resources
  x-api-slug: data-gov-api
  description: List all community resources
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/community_resources/
  tags: Datasets, Community, Resources
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetscommunity-resources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetscommunity-resources-get-openapi.md
- name: Data.gov API Add Datasets Community Resources
  x-api-slug: data-gov-api
  description: Create a new community resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/community_resources/
  tags: Datasets, Community, Resources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetscommunity-resources-post-openapi.md
- name: Data.gov API Delete Datasets Community Resources Community
  x-api-slug: data-gov-api
  description: Delete a given community resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/community_resources/{community}/
  tags: Datasets, Community, Resources, Community
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetscommunity-resourcescommunity-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetscommunity-resourcescommunity-delete-openapi.md
- name: Data.gov API Get Datasets Community Resources Community
  x-api-slug: data-gov-api
  description: Retrieve a community resource given its identifier
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/community_resources/{community}/
  tags: Datasets, Community, Resources, Community
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetscommunity-resourcescommunity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetscommunity-resourcescommunity-get-openapi.md
- name: Data.gov API Put Datasets Community Resources Community
  x-api-slug: data-gov-api
  description: Update a given community resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/community_resources/{community}/
  tags: Datasets, Community, Resources, Community
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetscommunity-resourcescommunity-put-openapi.md
- name: Data.gov API Add Datasets Community Resources Community Upload
  x-api-slug: data-gov-api
  description: Update the file related to a given community resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/community_resources/{community}/upload/
  tags: Datasets, Community, Resources, Community, Upload
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetscommunity-resourcescommunityupload-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetscommunity-resourcescommunityupload-post-openapi.md
- name: Data.gov API Get Datasets Frequencies
  x-api-slug: data-gov-api
  description: List all available frequencies
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/frequencies/
  tags: Datasets, Frequencies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsfrequencies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsfrequencies-get-openapi.md
- name: Data.gov API Get Datasets Full
  x-api-slug: data-gov-api
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/full/
  tags: Datasets, Full
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsfull-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsfull-get-openapi.md
- name: Data.gov API Get Datasets Licenses
  x-api-slug: data-gov-api
  description: List all available licenses
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/licenses/
  tags: Datasets, Licenses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetslicenses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetslicenses-get-openapi.md
- name: Data.gov API Get Datasets Suggest
  x-api-slug: data-gov-api
  description: Suggest datasets
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/suggest/
  tags: Datasets, Suggest
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetssuggest-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetssuggest-get-openapi.md
- name: Data.gov API Get Datasets Suggest Formats
  x-api-slug: data-gov-api
  description: Suggest file formats
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/suggest/formats/
  tags: Datasets, Suggest, Formats
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetssuggestformats-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetssuggestformats-get-openapi.md
- name: Data.gov API Delete Datasets Dataset
  x-api-slug: data-gov-api
  description: Delete a dataset given its identifier
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/
  tags: Datasets, Dataset
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdataset-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdataset-delete-openapi.md
- name: Data.gov API Get Datasets Dataset
  x-api-slug: data-gov-api
  description: Get a dataset given its identifier
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/
  tags: Datasets, Dataset
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdataset-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdataset-get-openapi.md
- name: Data.gov API Put Datasets Dataset
  x-api-slug: data-gov-api
  description: Update a dataset given its identifier
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/
  tags: Datasets, Dataset
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdataset-put-openapi.md
- name: Data.gov API Add Datasets Dataset Badges
  x-api-slug: data-gov-api
  description: Create a new badge for a given dataset
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/badges/
  tags: Datasets, Dataset, Badges
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetbadges-post-openapi.md
- name: Data.gov API Delete Datasets Dataset Badges Badge Kind
  x-api-slug: data-gov-api
  description: Delete a badge for a given dataset
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/badges/{badge_kind}/
  tags: Datasets, Dataset, Badges, Badge, Kind
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetbadgesbadge-kind-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetbadgesbadge-kind-delete-openapi.md
- name: Data.gov API Delete Datasets Dataset Featured
  x-api-slug: data-gov-api
  description: Unmark the dataset as featured
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/featured/
  tags: Datasets, Dataset, Featured
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetfeatured-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetfeatured-delete-openapi.md
- name: Data.gov API Add Datasets Dataset Featured
  x-api-slug: data-gov-api
  description: Mark the dataset as featured
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/featured/
  tags: Datasets, Dataset, Featured
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetfeatured-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetfeatured-post-openapi.md
- name: Data.gov API Get Datasets Dataset Full
  x-api-slug: data-gov-api
  description: Get a dataset given its identifier
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/full/
  tags: Datasets, Dataset, Full
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetfull-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetfull-get-openapi.md
- name: Data.gov API Add Datasets Dataset Resources
  x-api-slug: data-gov-api
  description: Create a new resource for a given dataset
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/resources/
  tags: Datasets, Dataset, Resources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetresources-post-openapi.md
- name: Data.gov API Put Datasets Dataset Resources
  x-api-slug: data-gov-api
  description: Reorder resources
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/resources/
  tags: Datasets, Dataset, Resources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetresources-put-openapi.md
- name: Data.gov API Delete Datasets Dataset Resources R
  x-api-slug: data-gov-api
  description: Delete a given resource on a given dataset
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/resources/{rid}/
  tags: Datasets, Dataset, Resources, R
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetresourcesrid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetresourcesrid-delete-openapi.md
- name: Data.gov API Put Datasets Dataset Resources R
  x-api-slug: data-gov-api
  description: Update a given resource on a given dataset
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/resources/{rid}/
  tags: Datasets, Dataset, Resources, R
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetresourcesrid-put-openapi.md
- name: Data.gov API Add Datasets Dataset Resources R Upload
  x-api-slug: data-gov-api
  description: Upload a file related to a given resource on a given dataset
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/resources/{rid}/upload/
  tags: Datasets, Dataset, Resources, R, Upload
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetresourcesridupload-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetresourcesridupload-post-openapi.md
- name: Data.gov API Add Datasets Dataset Upload
  x-api-slug: data-gov-api
  description: Upload a new dataset resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/upload/
  tags: Datasets, Dataset, Upload
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetupload-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetupload-post-openapi.md
- name: Data.gov API Add Datasets Dataset Upload Community
  x-api-slug: data-gov-api
  description: Upload a new community resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{dataset}/upload/community/
  tags: Datasets, Dataset, Upload, Community
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetuploadcommunity-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsdatasetuploadcommunity-post-openapi.md
- name: Data.gov API Delete Datasets  Followers
  x-api-slug: data-gov-api
  description: Unfollow an object given its ID
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{id}/followers/
  tags: Datasets, , Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsidfollowers-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsidfollowers-delete-openapi.md
- name: Data.gov API Get Datasets  Followers
  x-api-slug: data-gov-api
  description: List all followers for a given object
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{id}/followers/
  tags: Datasets, , Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsidfollowers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsidfollowers-get-openapi.md
- name: Data.gov API Add Datasets  Followers
  x-api-slug: data-gov-api
  description: Follow an object given its ID
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///datasets/{id}/followers/
  tags: Datasets, , Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsidfollowers-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/datasetsidfollowers-post-openapi.md
- name: Data.gov API Get Me Datasets
  x-api-slug: data-gov-api
  description: List all my datasets (including private ones)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///me/datasets/
  tags: Me, Datasets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/medatasets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/medatasets-get-openapi.md
- name: Data.gov API Get Me Org Datasets
  x-api-slug: data-gov-api
  description: List all datasets related to me and my organizations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///me/org_datasets/
  tags: Me, Org, Datasets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/meorg-datasets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/meorg-datasets-get-openapi.md
- name: Data.gov API Get Organizations Org Datasets
  x-api-slug: data-gov-api
  description: List organization datasets (including private ones when member)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///organizations/{org}/datasets/
  tags: Organizations, Org, Datasets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/organizationsorgdatasets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/organizationsorgdatasets-get-openapi.md
- name: Data.gov API Add Reuses Reuse Datasets
  x-api-slug: data-gov-api
  description: Add a dataset to a given reuse
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///reuses/{reuse}/datasets/
  tags: Reuses, Reuse, Datasets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/reusesreusedatasets-post-openapi.md
- name: Data.gov API Get Site Home Datasets
  x-api-slug: data-gov-api
  description: List homepage datasets
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///site/home/datasets/
  tags: Site, Home, Datasets
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/sitehomedatasets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/sitehomedatasets-get-openapi.md
- name: Data.gov API Put Site Home Datasets
  x-api-slug: data-gov-api
  description: Set the homepage datasets editorial selection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3///site/home/datasets/
  tags: Site, Home, Datasets
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/sitehomedatasets-put-openapi.md
- name: Data.gov API
  x-api-slug: data-gov-api
  description: data.gov is a U.S. government website launched in late May 2009 by
    the then Federal Chief Information Officer (CIO) of the United States, Vivek Kundra.
    According to its website, The purpose of data.gov is to increase public access
    to high value, machine readable datasets generated by the Executive Branch of
    the Federal Government. The site seeks to become a repository for all the information
    the government collects. The site would publish to the public any data that is
    not private or restricted for national security reasons.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/data-gov-logo.png
  humanURL: http://data.gov/
  baseURL: https://catalog.data.gov//api/3/
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/data-gov/openapi.md
x-common:
- type: x-blog
  url: https://www.data.gov/meta/
- type: x-blog-rss
  url: https://www.data.gov/feed/
- type: x-developer
  url: http://developer.data.gov/
- type: x-signup
  url: https://api.data.gov/signup/
- type: x-twitter
  url: https://twitter.com/usdatagov
- type: x-website
  url: http://data.gov/
- type: x-wikipedia
  url: http://en.wikipedia.org/wiki/Data.gov
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---