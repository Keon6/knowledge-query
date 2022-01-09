# knowledge-query
Endpoints for the world's most impactful data scattered across the online and offline worlds.

## Goal
Finding good data sources in many research domains is often time consuming. Even when we do know a good source exists, it's difficult to navigate through it. Or sometimes, those sources don't actually cover all the data that is available out there. Let's collect all major data sources in variety of research fields (ie. Life Sciences, Metallurgy, and Finance) & create a frictionless and easy access via an API. 

## Who Should Contribute?
If you are a researcher, a developer, or just an interested individual who regularly makes use of variety of data sources in research domains, you might be just the right person. Particularly if you often have trouble finding good sources or navigating through the sources. Help us solve the data accessibility problem!


## How to Contribute?
You can contributes in 3 ways.
1) Send us the sources
  If you know where the data is & want to help others discover it too, then please help us keep track of those sources
2) Verify the sources for us
  If you have used a particular data source or are interested in trying it out, then help us verify the source
3) Build endpoints for us 
  If you want to help design easier ways to interact with data, then please help us build the endpoints

### Workflow
Each source will go through a simple 3 step process to keep track of the status.

Source Idenitification -> Source Validation -> Endpoint Design


#### Source Identification
Please submit a form containing a URL source, brief description, and potential use cases.

#### Source Validation
We want to make sure that the data we work on are indeed useful data. Criteria we're looking for are:
1) Impact: Does this data have commercial, academic, or public value? Does this data contain actually useful information? Can you back up the value by citing actual use cases on who used this data, how, and what for?
2) Validity: Is the data indeed what it says it is?

If the answers to the above seem valid, then let's start building the endpoints

#### Endpoint Design
This is the most important part. This is up to your discretion but when in doubt some principle to follow are - make it easy to to use, don't drop any relevant information, and keep it simple.

## Data Domains
The below are domains suffering from data scattering problem. Please feel free to suggest new domains/subdomains.

### Life Sciences

### Mettalurgy

### Finance
#### Private Markets
#### Public Markets
#### Crypto Markets

## Keeping Track of Sources
The repository will keep track of at which step each source is, given by the directory as below
```
knowledge-query/
  identified_sources/
    domain_1/
      subdomain_1.txt
      subdomain_2.txt
      ...
      suddomain_n.txt
    domain_2/...
    ...
    domain_m/...
  verified_sources/...
  verification_failed/...
  endpoints_built/...
```

Each source will be recorded as a row in each text file (in a comma separated format) with its URL, brief description, and potential use cases.
IF the source if offline, then please upload the URL for a digitized version of it.
