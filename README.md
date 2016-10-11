# semantic-ui

Holds the semantic-ui distribution used to make the custom theme for techfolios.

This distribution of semantic-ui was installed using NPM. See [Semantic UI, Getting Started](http://semantic-ui.com/introduction/getting-started.html) for more details.

Customizations:

  * src/themes/default/globals/site.variables:  made Open Sans the default font.
  * src/themes/default/views/card.variables: I changed the @description and @extracontent color definitions to use textColor so the text wouldn't be so light.
  
If you are downloading this from GitHub, the node_modules directory needs to be built.  I think you can do this with:

  * `npm install`
  
To update to a new release of semantic-ui, I think it's as simple as:

  * `npm update`
  
To build and install a new version, cd into the semantic/ directory, then invoke:

  * `gulp build`
  * `install-dist.sh`
