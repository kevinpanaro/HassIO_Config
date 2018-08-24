# Hass.io Configuration

Here's my Home Assistant configuration files. As you can see, I use folders to organize and seperate my components as much as I can. 

## Main Config Files
 - [configuration.yaml]: As you can see, almost all of my configurations utilize the !include functionality of yamls.
 - [customize.yaml]: This is where I customize all of my components.

### Config Folders
 - [alexa]: All things Alexa. A unique folder structure due to how the alexa smart home component is set up.
 - [automations]: Standard !include, but I'll split these up to have the file name match whats being automated.
 - [cover]: Any cover here, !include_dir_merge_list, so split into lists of types of covers.
 - [device_tracker]: Same as cover, usually split into the component type
 - [group]: Uses !include_dir_merge_named, and splits up into types of groups
 - [homekit]: All homekit things. Again super unique folder structure just like alexa
 - [input_boolean]: Straight forward
 - [input_number]: Also Straight forward
 - [input_select]: These three (^^) are pretty boring, because their simple components
 - [ios]: Another super unique folder structure. but all things ios.
 - [light]: split up by component type, so mqtt_json might get big.
 - [media_player]: similar to light except grouped together with type of media player component
 - [notify]: boring, and empty because I use ios only as my notification system right now.
 - [scene]: boring again, and unused
 - [script]: each script is in its own folder which just makes sense.
 - [sensor]: each sensor has its own file
 - [themes]: each theme is its own... again...
 - [www]: local files, and pictures of my face.


### Todos

 - Add more components
 - Buy more components
 - Automate

License
----

MIT


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [alexa]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/alexa>
   [automations]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/automations>
   [cover]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/cover>
   [configuration.yaml] <https://github.com/kevinpanaro/HassIO_Config/blob/master/configuration.yaml>
   [customize.yaml] <https://github.com/kevinpanaro/HassIO_Config/blob/master/customize.yaml>
   [device_tracker]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/device_tracker>
   [group]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/group>
   [homekit]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/homekit>
   [input_boolean]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/input_boolean>
   [input_number]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/input_number>
   [input_select]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/input_select>
   [ios]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/ios>
   [light]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/light>
   [media_player]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/media_player>
   [notify]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/notify>
   [scene]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/scene>
   [script]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/script>
   [sensor]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/sensor>   
   [themes]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/themes>
   [www]: <https://github.com/kevinpanaro/HassIO_Config/tree/master/www>

