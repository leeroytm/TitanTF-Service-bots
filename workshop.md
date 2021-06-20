[[ALERT!]]
This applet uses EntryContent module!
The applet may or may not work because of too many requests to this host.

Original:
{ "username":"New Workshop Submission", "content":"`[⚙️]` **[{{EntryTitle}}]({{EntryUrl}})** \n • Submitted on {{EntryPublish}} by {{EntryAuthor}}" }

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

New:
{
  "embeds": [
    {
      "title": "{{EntryTitle}}",
      "url": "{{EntryUrl}}",
      "description": "{{EntryContent}}",
      "color": 4886754,
      "footer": {
        "text": "Submit : {{EntryPublished}} by {{EntryAuthor}} "
      },
      "author": {
        "name": "Titan.TF Workshop",
        "url": "https://workshop.titan.tf/",
        "icon_url": "https://media.discordapp.net/attachments/776599695786508328/792389296584785921/tf2_logo.png?width=473&height=473"
      }
    }
  ]
}

Compact:
{"embeds": [{"title": "{{EntryTitle}}","url": "{{EntryUrl}}","description": "{{EntryContent}}","color": 4886754,"footer": {"text": "Submit : {{EntryPublished}} by {{EntryAuthor}} "},"author": {"name": "Titan.TF Workshop","url": "https://workshop.titan.tf/","icon_url": "https://media.discordapp.net/attachments/776599695786508328/792389296584785921/tf2_logo.png?width=473&height=473"}}]}
