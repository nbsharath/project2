# Front end start bean project 
The project provides intial setup that contains gulp tasks and folder structure that can be used for web application developemet. 

## The gulp tasks include:

  ### Java script task - build-js : 
    This task will concatinate all the js files under src/javascript file and minfies them and places with under      desc/javascript folde.
    run `gulp build-js`
  ### Styles task - styles: 
    This task will convert the sass files src/css into css file and minifies them and places it under desc/css folder.
    run `gulp styles`
  ### The html task - html:
    Copies the html file src/index.html to desc/index.html, the task can be enhanced to automaticallty add the javascript and css dependency depending upon the files under desc/javasctipt / desc/css.
    run `gulp html`
  ### The last task - watch: 
    This task will run all the above tasks one after the other when ever there is change in files. This task will automatically create the destination files whenever the source fiels is changed  by the author. Strat this task before you start developing.
    run `gulp watch`

## Further help 
Please reach out to me- sharathnb10@gmail.com.
    
