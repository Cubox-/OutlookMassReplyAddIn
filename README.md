# OutlookMassReplyAddIn
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FCubox-%2FOutlookMassReplyAddIn.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FCubox-%2FOutlookMassReplyAddIn?ref=badge_shield)

fuck outlook

This plugin is made for sending mass emails with the same content to a lot of people in outlook

## Why bother?

I work at a real estate agency, receiving about 100 emails a day generated by the contact form on various websites.
Outlook don't let you send mass reply to all of them. I need to send them the files they need for various operations.

Tired of sending emails one by one, I tried to look for a solution.
Making a rule that apply on a folder to send a reply as template? Nope, don't follow Reply-To.

## fuck outlook

Yeah. Fuck them. I had to make a fucking plugin for that shit. And I need it to be as stable as possible, since normal people will be using it.

### Your code is awful, why are you doing so much file copies and tempoary files!

Well, Outlook is really bad. You cannot save in memory the content of a section of an email to insert it into another one. You HAVE to save it to file, and then import it from the file.
Same for attachements, it's way too easy to just keep them in memory, you NEED to keep them on disk and add them ONE BY ONE for EACH EMAIL.

I hate Outlook.


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FCubox-%2FOutlookMassReplyAddIn.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FCubox-%2FOutlookMassReplyAddIn?ref=badge_large)