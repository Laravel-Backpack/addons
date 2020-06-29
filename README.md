# Backpack Addons

A place for the Backpack community to talk about possible Backpack add-ons.

--

## Why?

Starting with Backpack 4.1.x we're trying to move as many non-essential features as possible into Backpack add-ons. And especially new features. Moving features that are NOT used in the 80% use case to add-ons should:
- help the Backpack team focus more on maintaining features MOST people are using;
- give developers & veterans the opportunity to stand out and be recognised as the author of that feature, and a prominent member inside the Backpack community (by having their package listed on our Addons Page, their name inside the add-on repo, and more); they get eyeballs on themselves, their Github profiles or their businesses;
- help Backpack developers (end-users) to have a skinnier installation, if they don't need all the extra features, while still allowing them to use niche/opinionated features like this one whenever they need;

It's recommended that you create a Backpack add-on if:
- that feature would work well inside more projects - yours or other people's;
- you intend to maintain the add-on in the future (fix possible bugs that your users report, make changes to support new versions of Backpack);

It's recommended that you NOT create a Backpack add-on if:
- the feature is very specific to your project;
- you do not intend to maintain the add-on in the future (in this case it's better to open an issue to propose the add-on and say you don't have the time to maintain it);

You can create a Backpack add-on even if you've never created an open-source project before. In fact, it's the perfect kind of project to start with, we've written the tutorials with you in mind. So yes, a Backpack add-on would make an excellent first open-source project.


## Process

Its goal is to move issues inside [the Projects](https://github.com/Laravel-Backpack/addons/projects):
- from Idea
- to Good Idea
- to Claimed / WIP
- to Done
- to In Review
- to Finished / Scrapped

When finished, add-ons are to be:
- posted on https://backpackforlaravel.com/addons
- promoted on [our sub-Reddit](https://www.reddit.com/r/BackpackForLaravel/)
- promoted on [our Gitter Chatroom](https://gitter.im/BackpackForLaravel/Lobby)
- promoted inside our next bi-annual newsletter
- promoted with a post on [our Blog](https://backpackforlaravel.com/articles)
- promoted inside our weekly/monthly newsletter (automatically gets sent if there's a blog post about it)
- posted about on [Laravel News](https://laravel-news.com/)

In total, the reach is 17.000+ Laravel developers.


## Resources

This is where you can learn to create a Backpack add-on:
- [How to create an add-on for a custom field](https://backpackforlaravel.com/docs/4.1/add-ons-tutorial)
- How to create an add-on for a custom column - TODO, very similar to Fields above;
- How to create an add-on for a custom filter - TODO, very similar to Fields above;
- How to create an add-on for a custom button - TODO, very similar to Fields above;
- [How to create an add-on for an operation](https://backpackforlaravel.com/docs/4.1/add-ons-custom-operation)
- How to create an add-on with one CRUD - TODO (end result would be similar to [MenuCRUD](https://github.com/Laravel-Backpack/menucrud));
- How to create an add-on with multiple CRUDs - TODO (end result would be similar to [NewsCRUD](https://github.com/laravel-backpack/newscrud));

We plan to make it easier to create Backpack add-ons, so please give feedback on our process, write articles, submit PRs, anything you can do to help in this regard is very appreciated - it's not easy for us to see the process from an outside perspective.


## Naming Conventions

When creating a new backpack add-ons, it's recommended that the name itself is as explicit as possible. A general rule would be to:
- include the feature name
- include the feature type (field, column, filter, operation, crud, etc)
- include the `for-backpack` suffix in the name, so people find it when looking for `backpack`;

Good examples:
- `vendorname/toggle-field-for-backpack`
- `vendorname/revise-operation-for-backpack`
- `vendorname/gutenberg-field-for-backpack`
- `vendorname/invoice-crud-for-backpack`

Not-so-good examples:
- `vendorname/toggle-field` - since it doesn't have Backpack in the name less people are going to find it;
- `vendorname/toggle` - does not specify the feature type so it's not obvious what it provides - a field? a column? a filter? what is it?

## Feedback

Please open an issue inside this repo if you have thoughts about how we create add-ons. We appreciate it.
