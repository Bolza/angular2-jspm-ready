# Angular2 Upgrade Module (#7525 fix)

This is a temporary and not very smart repository.
I wouldn't recommend anyone to use it. Unless you have these errors:

`Expecting HostViewFactoryRef for:`
or
`Expecting ComponentFactory for:`

Is meant to provide a JSPM package for the `Upgrade Module` of [angular2-RC.1](https://github.com/angular/angular) with the fix of [#7525 Issue](https://github.com/angular/angular/issues/7525) waiting for the NG2 guys to actually merge the PR.

The repo is not forked and therefore will not be mantained, actually it will probavbly be deleted after the next NG2 release.

The base install of the NG2 JSPM package from the actual angular repo is done using
> jspm i npm:@angular/core@2.0.0-rc.1 npm:@angular/common@2.0.0-rc.1 npm:@angular/compiler@2.0.0-rc.1 npm:@angular/http@2.0.0-rc.1 npm:@angular/platform-browser@2.0.0-rc.1 npm:@angular/platform-browser-dynamic@2.0.0-rc.1 npm:@angular/router@2.0.0-rc.1

Then you can install this package instead of `npm:@angular/upgrade@2.0.0-rc.1`
> jspm i github:Bolza/angular2-jspm-ready@0.4

Then add/replace these paths in your `config.js`
	
	map: {
	    "@angular/upgrade": "github:Bolza/angular2-jspm-ready@0.4",
	    "@angular/upgrade@2.0.0-rc.1": "github:Bolza/angular2-jspm-ready@0.4",
	    "angular2/upgrade": "github:Bolza/angular2-jspm-ready@0.4"
	}

