##Creating the deliverable

First you need to create the hooks to your `client` folder.

    yo angular-famous-ionic:target myapp --mobile
    
Then create the distributable

    gulp dist --t myapp
    
You navigate to the folder

    cd dist/maypp/<dev or prod>/
    
And just instantiate PhoneGap

    phonegap platform add <ios or android or ...>
    
