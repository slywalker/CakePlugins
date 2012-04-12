#My favorite CakePHP2.x plugins

This is collection of my favorite CakePHP2.x plugins.

##Install

Add submodule into your project repository

	git submodule add git://github.com/slywalker/CakePlugins.git
	git submodule init --recursive

Add your app/Config/bootstrap.php

	App::build(array('Plugin' => array('/path/to/your/CakePlugins' . DS)));
	CakePlugin::load('PluginNameYouWantUse');

##Update

	git submodule update --init --recursive
