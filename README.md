# Cookiecutter Kolibri Plugin
Minimal [Cookiecutter](https://github.com/audreyr/cookiecutter) template for generating [Kolibri](https://github.com/learningequality/kolibri) plugins.

## Usage

* Install Cookiecutter.

  `$ pip install cookiecutter`


* Generate a new Kolibri plugin within the directory of your choice.

  `$ cookiecutter https://github.com/learningequality/cookiecutter-kolibri-plugin`


* Select a plugin name. 
  
  Must be `lowercase_separated_by_underscores` (ie. `vector_video_player`).


* Select a plugin Class name. 
  
  Must be `UpperCamelCase.` (ie. `VectorVideoPlayer`).


* Install the newly generated plugin in Kolibri.

  `$ pip install -e <LOCAL_PATH_TO_THE_PLUGIN_DIRECTORY>`
  
  
* Enable the plugin on Kolibri.

  `$ kolibri plugin <plugin_name> enable`
  

* Restart the Kolibri server.


* You can test the plugin by visiting `http://127.0.0.1:8000/<plugin_name>`
