# selenium-basic-test

Sample tests created with Selenium IDE. The execution can be performed with Selenium IDE command line runner

# Installation

1. Install NodeJS https://nodejs.org/
2. Install the browser driver:

   Chrome:
      `npm install -g chromedriver`
      
   Firefox:
      `npm install -g geckodriver`
      
   Edge:
      `npm install -g edgedriver`


# Usage

To run your tests locally execute the following from the CLI (e.g using chrome):

`selenium-side-runner -c "browserName=chrome" tests/petstore.side`
