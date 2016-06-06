# angular2-jspm-ready

This is a temporary and not very smart repository.

I wouldn't recommend anyone to use it.

Is meant to provide a JSPM package for [angular2-RC.1](https://github.com/angular/angular) with the fix of [#7525 Issue](https://github.com/angular/angular/issues/7525) waiting for the NG2 guys to actually merge the PR.

The repo is not forked and therefore will not be mantained, actually will probavbly be deleted after the next NG2 release.

The base install of the NG2 JSPM package from the actual angular repo is done using
> jspm i npm:@angular/core@2.0.0-rc.1 npm:@angular/common@2.0.0-rc.1 npm:@angular/compiler@2.0.0-rc.1 npm:@angular/http@2.0.0-rc.1 npm:@angular/platform-browser@2.0.0-rc.1 npm:@angular/platform-browser-dynamic@2.0.0-rc.1 npm:@angular/router@2.0.0-rc.1

Then you can install this package 
> jspm i github:Bolza/angular2-jspm-ready@0.3
