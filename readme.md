# MW Grid System

## information

### Author
Takashi Kitajima

### Author URI
http://2inc.org

### Created
December 11, 2014

### Modified
January 15, 2015

## Sample code

    <div class="row">
      <div class="col-12">
        Centering box. This box max width is 1170px.
      </div>
      
      <div class="col-md-12">
        Centering box. This box max width is 940px.
      </div>
      
      <div class="col-12">
        <div class="row">
          <div class="col-5 offset-1 col-xs-6">
            This column has been splitted when also smartphone size.
          </div>
          <div class="col-6 col-xs-6">
            This column has been splitted when also smartphone size.
          </div>
        </div>
        
        <div class="row">
          <div class="col-sm-6"></div>
          <div class="col-sm-6"></div>
        </div>
        
        <div class="row">
          <div class="col-6">
            <div class="row">
              <div class="col-6"></div>
              <div class="col-6"></div>
            </div>
          </div>
          <div class="col-6"></div>
        </div>
      </div>
    </div>

### Change log

#### 1.0.0
* Initial commit.

### License
GPLv2
http://www.gnu.org/licenses/gpl-2.0.html
Window size: 1038 x 840
Viewport size: 1038 x 732