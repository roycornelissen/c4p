# Send a proposal #

Do you think you have a cool idea for a talk?
Fork the repo, add your proposal/s to the array in the [json](proposal.json) and send your PR

```json
{
    "proposal": [{
        "title": "Title of the speech",
        "description": "Tell me something to convince me that your proposal is very cool",
        "tags": ["aspnet vnext", "nodejs", "ruby", "angulars"],
        "author": {
            "firstname": "Ugo",
            "lastaname": "Lattanzi",
            "twitter": "@imperugo",
            "blog": "http://tostring.it",
            "bio": "Ugo is a programmer specialized in enterprise application, with focus in web applications, service oriented applications and, generally, in all the environments where scalability is a top priority. Thanks to the experience earned in the latest years, Ugo is now focused on technologies like ASP.NET MVC, NodeJS, Azure, NServiceBus Nhibernate and HTML5. Thanks to this passion in web development using ASP.NET MVC, Microsoft granted him the MVP Award in this technology. Speaker for the most important Italian communities, Author of several articles and co-organizer of the widely appreciated Web.NET European Conference in 2012. Away from keybord he's a bad snowboarder but a good father.",
            "avatarUrl": "https://avatars1.githubusercontent.com/u/758620?s=460"
        }
    }]
}
```

Hey, to accept your PR, your code must be Valid JSON, so check it [here](http://jsonlint.com/)
