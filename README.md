# Angular-NodeJS---The-MEAN-Stack-Guide
Angular &amp; NodeJS - The MEAN Stack Guide - Udemy Course Notes

## Section 1
### Getting Started
- MEAN ( Mongo, Express, Angular, Node)
- Install Node, Angular CLI `npm install -g @angular/cli`
- ng serve will serve in default port and host.
- To change the host and port, added `"port": 8080", "host": "0.0.0.0"` in "serve" object inside angular.json file.
- Basic default app served.
- Learned the angular app folder components.

## Section 2
### The Angular Frontend - Understanding the Basics
- created a new post-create component.
- Different types of getting a value from the class.
	```html
	<textarea rows="6" [value]="newPost"></textarea>
	<hr>
	<button (click)="onAddPost()">Save Post</button>
	<p>{{ newPost }}</p>
	```
- Learned abo
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMDc5MTk3NDksMTUzMTI2ODcxMiwtMT
YyNjg5OTcyMiwxNDE0ODExNTA5LC00NzUyODczMDEsLTY2Mzc5
NDEyMSwxMTQ5NzE0NDc3LC0xNjk4MzgzMzI5XX0=
-->