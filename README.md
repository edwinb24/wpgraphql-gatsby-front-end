# wpgraphql-gatsby-front-end
Front-end initial setup ready to use for WPGraphQL Gatsby Projects

Remember to change the gatsby-source-graphql plugin source url to http://mytestpage.com/graphql? in the gatsby-config file. 

Running your first query...
Stop gatsby develop if it was running and re-run the command.
Go to port http://localhost:8000/___graphql

Test Query:

{
  pages {
    nodes {
      title
      id
    }
  }
}

This should return all the pages titles and ids.
