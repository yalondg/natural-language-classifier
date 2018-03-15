---

copyright:
  years: 2015, 2018
lastupdated: "2018-03-16"

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}
{:tip: .tip}
{:pre: .pre}
{:codeblock: .codeblock}
{:screen: .screen}

# Release notes

The following new features and changes to the service are available.
{: shortdesc}

## Beta features
{: #beta}

{{site.data.keyword.IBM_notm}} releases services, features, and language support for your evaluation that are classified as beta. These features might be unstable, might change frequently, and might be discontinued with short notice. Beta features also might not provide the same level of performance or compatibility that generally available features provide and are not intended for use in a production environment. Beta features are supported only on [developerWorks Answers ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://developer.ibm.com/answers/topics/natural-language-classifier.html){: new_window}.

## Changes
{: #changelog}

The following new features and changes to the service are available.

### 16 March 2018
{: #16march2018}

- **Classify multiple phrases**

    A new **Classify multiple phrases** method is available that supports sending up to 30 text phrases in one request. The `POST /v1/classifiers/{classifier_id}/classify_collection` method supports classifying phrases in the same languages as for the original method, except for Japanese, which launches as a beta feature.

    For details about the API call, see the **Classify multiple phrases** method in the [API reference ![External link icon](../../icons/launch-glyph.svg "External link icon")](http://www.ibm.com/watson/developercloud/natural-language-classifier/api/v1/curl.html?curl#classify-multiple-phrases){:new_window}.

- **Train with larger data sets**

    You can now include up to 20,000 records in your training data. Classifier training is now enhanced by IBM Deep Learning as a Service. This offering is a neural network training infrastructure that uses an elastic cluster of graphics processing units (GPU) to handle larger data sets. The maximum size of the training data remains at 15,000 records for users in the Frankfurt region or users with IBM Cloud Dedicated.

### 10 July 2017
{: #10july2017}

**Additional languages:** The service now supports Korean in addition to Arabic, English, French, German, Japanese, Italian, Portuguese, and Spanish. The language of the training data must match the language of the text that you intend to classify.

For details about languages, see [Using your own data](/docs/services/natural-language-classifier/using-your-data.html#languages). For details about the API call, see the `Create classifier` method in the [API reference ![External link icon](../../icons/launch-glyph.svg "External link icon")](http://www.ibm.com/watson/developercloud/natural-language-classifier/api/v1/){:new_window}.

### 06 April 2016
{: #06april2016}

**Additional languages:** The service now supports German in addition to Arabic, English, French, Japanese, Italian, Portuguese, and Spanish. The language of the training data must match the language of the text that you intend to classify.

### 29 February 2016
{: #29february2016}

**Additional languages:** The service now supports Japanese in addition to Arabic, English, French, Italian, Portuguese, and Spanish.

### 7 December 2015
{: #07december2015}

**Additional languages:** The service now supports Arabic, French, and Italian in addition to English, Portuguese, and Spanish.

### 16 November 2015
{: #16november2015}

**Additional languages:** The service now supports Portuguese and  Spanish languages in addition to English.
