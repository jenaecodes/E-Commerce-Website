# E-Commerce Website
# Brand: "Kitchen Simply"


<img src="images/KS.png" alt="Logo" width="320" height="370">

## About The Project

This is a capstone project for my Software Engineer Apprenticeship at Year Up.

Here's why:
* Your time should be focused on creating something amazing. A project that solves a problem and helps others
* You shouldn't be doing the same tasks over and over like creating a README from scratch
* You should implement DRY principles to the rest of your life :smile:

Of course, no one template will serve all projects since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue. Thanks to all the people have contributed to expanding this template!

## Project Goals

- Create an intuitive flow
- 
- 
- 

### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* HTML5
* CSS3
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]
* JavaScript

### Requirements

1. A Home Page:
- Must have at least one stand-alone image
- Must have at least two paragraphs of text
- Must incorporate a bulleted or numbered list with at least 2 list items

2. A User Registration Page:
- Must have an HTML form with user name, password, password confirmation and email fields
- Must have a set of radio buttons with responses to the question "How did you hear about us?"
- Must include appropriate HTML validation attributes

3. A User Login Page:
- Must have an HTML form with user name and password fields
- Must have a remember me checkbox
- Must include appropriate HTML validation attributes

4. A Products and/or Services Page:
- Must list at least 6 products or services that are offered with a button that allows them to be ordered or added to a cart
- Each product/service must be described using a Bootstrap Card and each must contain an image

5. A Checkout Page:
- Must have an HTML form with appropriate input fields, a select field, and a submit button for purchaser information
- Input fields must include appropriate HTML validation attributes (ex: required, max length, etc.)
- Must contain an HTML table displaying at least 3 rows of sample data for items in the cart

### Interesting Piece of HTML/CSS

1. Hover Effect Over Gallery Images
2. In Pages > `product.html` make sure `hubConnection = new HubConnectionBuilder().WithUrl("http://localhost:7071/api").Build();` is set to the port your API is running on.


  ```json
  {
    "IsEncrypted": false,
    "Values": {
      "AzureWebJobsStorage": "UseDevelopmentStorage=true",
      "FUNCTIONS_WORKER_RUNTIME": "dotnet-isolated",
      "OPENAI_API_KEY": "",
      "AzureSignalRConnectionString": ""
    },
    "Host": {
      "CORS": "*"
    }
  }
  ```
  3. `styles.css`

## How it works

The API is powered by [Azure Durable Functions](https://learn.microsoft.com/azure/azure-functions/durable/durable-functions-overview?tabs=csharp-inproc). It uses [YouTube Explode](https://github.com/Tyrrrz/YoutubeExplode) to get the caption track of the requested YouTube video, slices the caption track into segments, and sends that segment to [OpenAI API](https://platform.openai.com/docs/models/gpt-3-5) for a summary. The summary is then broadcasted to SignalR which the client app is connected to.


## Contact

Your Name - @jenaecodes

Project Link: [https://github.com/jenaecodes/E-Commerce-Website]
