# LiveWB
A smart <b>Live Weather Background</b> auto changer.

*LiveWB - Live Weather Background*, is a bash script which fetches images from EUMETSAT and combines them using ImageMagick,
in a nice arangement which is very pleasant to view as a desktop background.

By watching regularly LiveWB composite sattelite images, a viewer may observe more details about weather and soon 
to be able make a prediction for the next day.

LiveWB creates a composite image from up to three  almost real time satelite weather images,
and updates Gnome3 background, when it is needed.

Images from EUMETSAT's website cover Europe, Africa, part of Asia and part of south America.
There are many types showing rain, fog, wind, probability of fire, cloud coverage, etc.

LiveWB do it's best to be autoconfigured and at the same time to respect local and remote resources.

Autoconfiguration includes: country discovery, update interval recognition,  maximized window recognition.

This means that without any configuration, a user will have as background a composite image which will be specifically
made for his country, and this composite image will update only if there is a newer image upstream and
at the same time there is none maximized window.

Custom configuration files may be created easily with the following parameters:</br>
- Composite image dimensions</br>
- Upstream image url (up to three)</br>
- Image's positions</br>
- Text info position</br>
- Legend type</br>
- Legend position

You can read more info about creating custom .config files at 'template.config'.

