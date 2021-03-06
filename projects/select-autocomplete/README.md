# MatSelectAutocomplete

MatSelectAutocomplete is Angular based material component with feature of multi-options selection and autocomplete features

Combination of drog (angular/material 8 update) and oak's forks of mat-select-autocomplete + 1 fix

[GitHub] (https://github.com/crono9977/mat-select-autocomplete)
[Demo] (https://stackblitz.com/edit/mat-select-autocomplete)
[Documentation] (https://medium.com/@cryptoipl/angular-material-multi-select-with-autocomplete-113065d58dab)

## Changes

[1.4.5]
- Make search bar sticky

[1.4.2]
- Add fix to check if selectedValue is null to prevent some not a property of null errors
- Bumped package version to 1.4.2

## Features

<ul>
  <li> Autocomplete in mat-select : Search the options based on display value</li>
  <li> Unselect / Select All at single click</li>
  <li>  Ability to select / unselect partial list which is being filtered</li>
</ul>

## Installation
Install MatSelectAutocomplete with npm:
npm install crono-mat-select-autocomplete --save

## Dependency
Angular Material. Add it using [GettingStartedWithAngularMaterial].

## Usage
Install select-autocomplete using [npm]
In AppModule, import { SelectAutocompleteModule } from ‘select-autocomplete’;
Add it to your AppModule import list
Add material theme to your styles.scss as @import “~@angular/material/prebuilt-themes/indigo-pink.css”;
Add Material icons fonts to index.html as (<link href=”https://fonts.googleapis.com/icon?family=Material+Icons" rel=”stylesheet”>)
Now use <mat-select-autocomplete> with configurations specified in document


## Keywords
[angular], [angular2+], [angular2+], [angular6], [javascript], [material], [mat-select], [mat-select-autocomplete], [autocomplete]