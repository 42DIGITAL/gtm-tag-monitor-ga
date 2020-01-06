# Tag Monitor for GA

Tag Monitor for GA is a tag template that sends either name or id of the fired tags on Google Tag Manager to Google Analytics as a custom event. This will help analytics developers to monitor working and not working tags as a whole instead of testing every single tag once in a while.

  - Event Category: specified by user
  - Event Action: tag name or id
  - Event Label: page URL


### Installation
  - Simply import it from Google Tag Manager's Community Template Gallery or manually
  - Create a new tag by selecting this template under 'Custom' tag types
  - Add a trigger that fired on all events


### Setting up the tag
  - You can send tag name or tag id as event action. If tag name is intended, you need to set a key for tag name in every single tag's metadata. The name of those tags without a key (undefined) will not be sent.
  - Tag id would be a better choice if there exist so many tags which changing their metadata is tedious. You can download an overview of your container (which includes your tag ids) from www.gtmtools.com or using GTM API or downloading your GTM container as a JSON file and loading it into any tool (Notepad++ or even Google Data Studio can be helpful).

