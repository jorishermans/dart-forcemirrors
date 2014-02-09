### Dart Force Mirrors ###

![LOGO!](https://raw.github.com/jorishermans/dart-force/master/resources/dart_force_logo.jpg)

Part of the Dart Force Framework.

A mirrors helper library for the dart force framework

#### Walkthrough ####

This is how you can scrap the metadata info from an object. 

	MetaDataHelper<MetaData> mirrorHelper = new MetaDataHelper<MetaData>();
  	List<MetaDataValue<MetaData>> mirrorModels = mirrorHelper.getMirrorValues(new Anno());
  	
The annotated class.

	class Anno {
  
	  @MetaData("test")
	  void test() {}
	  
	}

MetaDataValue has the following fields:

	Symbol memberName;
  	InstanceMirror instanceMirror;
  	T object;

### Notes to Contributors ###

#### Fork Dart Force MVC ####

If you'd like to contribute back to the core, you can [fork this repository](https://help.github.com/articles/fork-a-repo) and send us a pull request, when it is ready.

If you are new to Git or GitHub, please read [this guide](https://help.github.com/) first.

#### Dart Force ####

Realtime web framework for dart that uses force MVC [source code](https://github.com/jorishermans/dart-force)

#### Twitter ####

Follow us on twitter https://twitter.com/usethedartforce

#### Google+ ####

Follow us on [google+](https://plus.google.com/111406188246677273707)