###  Generator
## Extending the view

    <div class="full-screen">
      <div class="bar bar-header bar-positive">
        <h1 class="title">Hello PhoneGap</h1>
      </div>
      <div class="bar bar-subheader bar-royal">
        <h2 class="title">and Angular, Yeoman, Gulp, Node, Bower</h2>
      </div>
      <fa-app ng-controller='main.common.hello as helloCtrl' class="three-quarters-height">    
          <fa-grid-layout fa-options="helloCtrl.myGridLayoutOptions" id="gridLayout">
          <fa-modifier ng-repeat="item in helloCtrl.list"
                         fa-translate="positions.centerContent"
                       fa-size="[90, 90]"
                       fa-origin="[0.5, 0.5]"
                       fa-align="[0.5, 0.5]"
                       fa-rotate-z="item.rotate.get()">
              <fa-surface fa-background-color="item.firstColor" 
                            fa-click="helloCtrl.click(item)" 
                            fa-color="'#fff'"> 
                    <i style="font-size: 3em; margin-left:0.8em;" class="icon {{item.firstIcon}}"></i>
              </fa-surface>
          </fa-modifier>
        </fa-grid-layout>
      </fa-app>
      <div class="bar bar-footer bar-balanced">
        <div class="title">and Ionic and Famo.us</div>
      </div>
    </div>