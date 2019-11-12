# Angular7

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

PS C:\Users\euscomh\Documents\GitHub\WebApiAngularAuthentication\Angular7> ng serve -o
Could not find module "@angular-devkit/build-angular" from "C:\\Users\\euscomh\\Documents\\GitHub\\WebApiAngularAuthentication\\Angular7".
Error: Could not find module "@angular-devkit/build-angular" from "C:\\Users\\euscomh\\Documents\\GitHub\\WebApiAngularAuthentication\\Angular7".
    at Object.resolve (C:\Users\euscomh\AppData\Roaming\npm\node_modules\@angular\cli\node_modules\@angular-devkit\core\node\resolve.js:141:11)
    at Observable.rxjs_1.Observable [as _subscribe] (C:\Users\euscomh\AppData\Roaming\npm\node_modules\@angular\cli\node_modules\@angular-devkit\architect\src\architect.js:132:40)
    at Observable._trySubscribe (C:\Users\euscomh\AppData\Roaming\npm\node_modules\@angular\cli\node_modules\rxjs\internal\Observable.js:44:25)
    at Observable.subscribe (C:\Users\euscomh\AppData\Roaming\npm\node_modules\@angular\cli\node_modules\rxjs\internal\Observable.js:30:22)
    at C:\Users\euscomh\AppData\Roaming\npm\node_modules\@angular\cli\node_modules\rxjs\internal\Observable.js:99:19
    at new Promise (<anonymous>)
    at Observable.toPromise (C:\Users\euscomh\AppData\Roaming\npm\node_modules\@angular\cli\node_modules\rxjs\internal\Observable.js:97:16)
    at ServeCommand.initialize (C:\Users\euscomh\AppData\Roaming\npm\node_modules\@angular\cli\models\architect-command.js:88:94)
    at process._tickCallback (internal/process/next_tick.js:68:7)
    at Function.Module.runMain (internal/modules/cjs/loader.js:744:11)
To install angular module : npm install --save-dev @angular-devkit/build-angular

Schema validation failed with the following errors:
  Data path ".builders['app-shell']" should have required property 'class'.
Error: Schema validation failed with the following errors:
  Data path ".builders['app-shell']" should have required property 'class'.
    at MergeMapSubscriber._registry.compile.pipe.operators_1.concatMap.validatorResult [as project] (C:\Users\euscomh\Documents\GitHub\WebApiAngularAuthentication\Angular7\node_modules\@angular-devkit\core\src\workspace\workspace.js:215:42)
    at MergeMapSubscriber._tryNext (C:\Users\euscomh\Documents\GitHub\WebApiAngularAuthentication\Angular7\node_modules\rxjs\internal\operators\mergeMap.js:69:27)
    at MergeMapSubscriber._next (C:\Users\euscomh\Documents\GitHub\WebApiAngularAuthentication\Angular7\node_modules\rxjs\internal\operators\mergeMap.js:59:18)
    at MergeMapSubscriber.Subscriber.next (C:\Users\euscomh\Documents\GitHub\WebApiAngularAuthentication\Angular7\node_modules\rxjs\internal\Subscriber.js:67:18)
    at MergeMapSubscriber.notifyNext (C:\Users\euscomh\Documents\GitHub\WebApiAngularAuthentication\Angular7\node_modules\rxjs\internal\operators\mergeMap.js:92:26)
    at InnerSubscriber._next (C:\Users\euscomh\Documents\GitHub\WebApiAngularAuthentication\Angular7\node_modules\rxjs\internal\InnerSubscriber.js:28:21)
    at InnerSubscriber.Subscriber.next (C:\Users\euscomh\Documents\GitHub\WebApiAngularAuthentication\Angular7\node_modules\rxjs\internal\Subscriber.js:67:18)
    at MapSubscriber._next (C:\Users\euscomh\Documents\GitHub\WebApiAngularAuthentication\Angular7\node_modules\rxjs\internal\operators\map.js:55:26)
    at MapSubscriber.Subscriber.next (C:\Users\euscomh\Documents\GitHub\WebApiAngularAuthentication\Angular7\node_modules\rxjs\internal\Subscriber.js:67:18)
    at SwitchMapSubscriber.notifyNext (C:\Users\euscomh\Documents\GitHub\WebApiAngularAuthentication\Angular7\node_modules\rxjs\internal\operators\switchMap.js:86:26)
PS C:\Users\euscomh\Documents\GitHub\WebApiAngularAuthentication\Angular7> ng update @angular/cli @angular/core
