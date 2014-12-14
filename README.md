# Writing with Friends

The goal for this repository is to collect ideas and provide a place for people to get comments, feedback, insight, editing help, and much more in one place.

## Contributing

You can help us write content at any step in the process. If you don’t feel like writing is your forte, you may just want to help by adding ideas or contributing ideas to other people’s posts. If you’re a great writer or editor, you may just post editing notes or grammatical fixes. Any level of contributions are more than welcome.

### Formatting

Your writing can be as long or as short as you want. Maybe it’s a simple quip or hundred word thing you’ve noticed. Maybe it’s a five hundred word explanation of a cool new technique. Maybe it’s 4000 words long and you could probably get your Masters for it. We just want good content, we don’t care about the length.

We also don’t care too much about formatting. Your writing should definitely have a title. It should somewhat follow ‘good essay structure’ although that may not apply in all cases. If you want to write in AP or MLA style, I don’t care.

> _Editors note: I actually care a little. Also, I like oxford commas._

### Structure

Please follow this example file structure for your writing:

```
\- writing-title-stub
  |- writing-title-stub.md
  \- assets
    |- asset.img
    |- asset.mov
```

The stub for your folder should match your branch name.

### Process

Contributions are sorted into milestones — there are:

1. [Ideas](#ideas)
1. [In Discussion](#in-discussion)
1. [In Writing](#in-writing)
1. [Ready for Review](#ready-for-review)
1. [In Review](#in-review)
1. [Ready to Publish](#ready-to-publish)
1. [Published](#published)

#### Ideas

The most basic level of contribution. This type of contribution takes the form of an issue posted to this repository. It can be as short as just a title explaining your idea or as detailed as you want. The goal of these issues is to make sure we’re recording all of the different ideas for content that we have so anyone can be inspired by them and work on them.

To submit an idea, go to [Issues](https://github.com/mobify/writing/issues?state=open) in the right sidebar and click the [New Issue button](https://github.com/mobify/writing/issues/new) in the top right. Add your idea to the title and any additional description or inspiration you want to the comments section. Apply an appropriate label and assign it to the `Idea` milestone.

#### In Discussion

These are ideas that are actively being commented on but haven’t started being written yet. Most ideas will move to this phase before they move into the writing phase although there’s no reason this phase couldn't be sidestepped altogether. Comments are no-holds barred discussions on the idea in question. There’s no limit on how long an idea can stay `In Discussion` and, sometimes, an `In Discussion` thread may spawn even more ideas for posts.

#### In Writing

An idea should be moved to the `In Writing` milestone as soon as there is an active branch being worked on. To start working on an idea, simply make a new branch with a descriptive name.

You should create a new Pull Request with your work as soon as you’re ready for people to look at it or help contribute. Your PR should reference the idea issue (or issues) that it addresses. To do this use the hashtag symbol (#) in the PR comments and Github will auto-suggest issues to help you. Make sure you also define the correct `In Writing` milestone for this new PR as well.

If you’re the kind of person that likes to have a full article written before you show anyone, that’s fine but be aware that someone else might be writing on the same topic. Getting a PR up with your post as soon as possible gives you a few opportunities:

1. Eyes on your article as soon as possible
1. Help with editing or writing passages
1. Fact check your assertions
1. Get parts written by other people

> Note: PRs won’t be merged until they’re ready so there’s no risk of having one open before your article is good to go. We’ll use the milestone tracker to know when a PR is ready to merge.

Once you've created your new branch and issued a new PR, feel free to close off the original issue. Since there is no way to just flow between an issue into a PR, you can close it off manually. If you go back to the issue, you'll notice that your PR reference is noted and you can now close things off.

Writing should stay in the `In Writing` milestone until the author or others feel it is `Ready for Review`. Once it’s in the `Ready for Review` stage, it will move speedily towards our next phases so don’t worry about posts stagnating in that section.

#### Ready for Review

This milestone marks articles that are ready for editing but haven’t been actively edited yet. People who like editing should feel free to grab articles from this milestone and move them to the `In Review` stage.

#### In Review

When an article is in editing, the PR should be moved to the `In Review` milestone. This milestone denotes articles that are actively being edited.

To edit an article, you can do one of several things:

1. **Suggestions** If you are making tone suggestions or have questions, simply post a comment on the PR.
1. **Small Changes** If you’re just making grammatical changes or suggestions, comments or direct commits are welcome.
1. **Large changes** If you need to make large scale changes, branch off of the PR and make a PR of your edits.

Like code reviews, article reviews should get +1s to denote that they’re ready to move into the `Ready to Publish` milestone.

#### Ready to Publish

This milestone is a list of articles that simply need +1s from anyone to merge it into master. Writing should have at least one +1 from a source not part of editing or authoring to get merged back in.

#### Published

This milestone will mostly hold closed issues and PRs that have already been published. It’s a good way for us to keep track of ideas that have already been covered so we can quickly sort through topics that have more or less coverage.
