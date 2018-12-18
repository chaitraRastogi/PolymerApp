# Your first Polymer element

This repo goes with the [Build your first Polymer element codelab](http://www.code-labs.io/codelabs/polymer-first-elements/).

The codelab is designed to be used with [Chrome Dev Editor](https://chrome.google.com/webstore/detail/chrome-dev-editor-develop/pnoffddplpippgcfjdhbmhkofpnaalpg?hl=en).
See the next section if you'd like to use another editor for the codelab.

## Running the codelab without Chrome Dev Editor

If you're not using CDE, you'll need to install some command-line tools to manage
dependencies and to run the demo.

1.  Download and install Node from [https://nodejs.org/](https://nodejs.org/). Node includes the node package manager command, `npm`.

2.  Install `bower` and `polymer-cli`:

        npm install -g bower

3.  Clone this repo:

        https://github.com/https://github.com/chaitraRastogi/PolymerApp
        
4.  Change directory to your local repo and install dependencies with `bower`:

        cd PolymerApp
        bower install
        
5.  To preview your element, run `polymer serve` from the repo directory:

        polymer serve
        
    Open `http://127.0.0.1:8081/components/Polymer sample app/` in your browser.
    
    Steps for running test cases
    
    1.Install Web component tester
     
     npm install -g web-component-tester
     
   2.Run the test cases
   
   $<path> wct
    

