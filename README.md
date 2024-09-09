# issue data field description
|data field|description|type|examples|
|:--|:--|:--|:--|
| Issue|"Issues are a great way to keep track of tasks, enhancements, and bugs for your projects."|object|""|
| id|""|integer|""|
| node_id|""|string|""|
| url|"URL for the issue"|string|"https://api.github.com/repositories/42/issues/1"|
| repository_url|""|string|""|
| labels_url|""|string|""|
| comments_url|""|string|""|
| events_url|""|string|""|
| html_url|""|string|""|
| number|"Number uniquely identifying the issue within its repository"|integer|42|
| state|"State of the issue; either 'open' or 'closed'"|string|"open"|
| state_reason|"The reason for the current state"|string|"not_planned"|
| title|"Title of the issue"|string|"Widget creation fails in Safari on OS X 10.8"|
| body|"Contents of the issue"|string|"It looks like the new widget form is broken on Safari. When I try and create the widget, Safari crashes. This is reproducible on 10.8, but not 10.9. Maybe a browser bug?"|
| user|"A GitHub user."|object|""|
|------ name|""|string|""|
|------ email|""|string|""|
|------ login|""|string|"octocat"|
|------ id|""|integer|1|
|------ node_id|""|string|"MDQ6VXNlcjE="|
|------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------ url|""|string|"https://api.github.com/users/octocat"|
|------ html_url|""|string|"https://github.com/octocat"|
|------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------ type|""|string|"User"|
|------ site_admin|""|boolean|""|
|------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
| labels|"Labels to associate with this issue; pass one or more label names to replace the set of labels on this issue; send an empty array to clear all labels from the issue; note that the labels are silently dropped for users without push access to the repository"|array|"bug"|
|------ labels|""|string|""|
|------ labels|""|object|""|
|------------ id|""|integer|""|
|------------ node_id|""|string|""|
|------------ url|""|string|""|
|------------ name|""|string|""|
|------------ description|""|string|""|
|------------ color|""|string|""|
|------------ default|""|boolean|""|
| assignee|"A GitHub user."|object|""|
|------ name|""|string|""|
|------ email|""|string|""|
|------ login|""|string|"octocat"|
|------ id|""|integer|1|
|------ node_id|""|string|"MDQ6VXNlcjE="|
|------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------ url|""|string|"https://api.github.com/users/octocat"|
|------ html_url|""|string|"https://github.com/octocat"|
|------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------ type|""|string|"User"|
|------ site_admin|""|boolean|""|
|------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
| assignees|""|array|""|
|------ assignees|"A GitHub user."|object|""|
|------------ name|""|string|""|
|------------ email|""|string|""|
|------------ login|""|string|"octocat"|
|------------ id|""|integer|1|
|------------ node_id|""|string|"MDQ6VXNlcjE="|
|------------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------------ url|""|string|"https://api.github.com/users/octocat"|
|------------ html_url|""|string|"https://github.com/octocat"|
|------------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------------ type|""|string|"User"|
|------------ site_admin|""|boolean|""|
|------------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
| milestone|"A collection of related issues and pull requests."|object|""|
|------ url|""|string|"https://api.github.com/repos/octocat/Hello-World/milestones/1"|
|------ html_url|""|string|"https://github.com/octocat/Hello-World/milestones/v1.0"|
|------ labels_url|""|string|"https://api.github.com/repos/octocat/Hello-World/milestones/1/labels"|
|------ id|""|integer|1002604|
|------ node_id|""|string|"MDk6TWlsZXN0b25lMTAwMjYwNA=="|
|------ number|"The number of the milestone."|integer|42|
|------ state|"The state of the milestone."|string|"open"|
|------ title|"The title of the milestone."|string|"v1.0"|
|------ description|""|string|"Tracking milestone for version 1.0"|
|------ creator|"A GitHub user."|object|""|
|------------ name|""|string|""|
|------------ email|""|string|""|
|------------ login|""|string|"octocat"|
|------------ id|""|integer|1|
|------------ node_id|""|string|"MDQ6VXNlcjE="|
|------------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------------ url|""|string|"https://api.github.com/users/octocat"|
|------------ html_url|""|string|"https://github.com/octocat"|
|------------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------------ type|""|string|"User"|
|------------ site_admin|""|boolean|""|
|------------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
|------ open_issues|""|integer|4|
|------ closed_issues|""|integer|8|
|------ created_at|""|string|"2011-04-10T20:09:31Z"|
|------ updated_at|""|string|"2014-03-03T18:58:10Z"|
|------ closed_at|""|string|"2013-02-12T13:22:01Z"|
|------ due_on|""|string|"2012-10-09T23:39:01Z"|
| locked|""|boolean|""|
| active_lock_reason|""|string|""|
| comments|""|integer|""|
| pull_request|""|object|""|
|------ merged_at|""|string|""|
|------ diff_url|""|string|""|
|------ html_url|""|string|""|
|------ patch_url|""|string|""|
|------ url|""|string|""|
| closed_at|""|string|""|
| created_at|""|string|""|
| updated_at|""|string|""|
| draft|""|boolean|""|
| closed_by|"A GitHub user."|object|""|
|------ name|""|string|""|
|------ email|""|string|""|
|------ login|""|string|"octocat"|
|------ id|""|integer|1|
|------ node_id|""|string|"MDQ6VXNlcjE="|
|------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------ url|""|string|"https://api.github.com/users/octocat"|
|------ html_url|""|string|"https://github.com/octocat"|
|------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------ type|""|string|"User"|
|------ site_admin|""|boolean|""|
|------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
| body_html|""|string|""|
| body_text|""|string|""|
| timeline_url|""|string|""|
| repository|"A repository on GitHub."|object|""|
|------ id|"Unique identifier of the repository"|integer|42|
|------ node_id|""|string|"MDEwOlJlcG9zaXRvcnkxMjk2MjY5"|
|------ name|"The name of the repository."|string|"Team Environment"|
|------ full_name|""|string|"octocat/Hello-World"|
|------ license|"License Simple"|object|""|
|------------ key|""|string|"mit"|
|------------ name|""|string|"MIT License"|
|------------ url|""|string|"https://api.github.com/licenses/mit"|
|------------ spdx_id|""|string|"MIT"|
|------------ node_id|""|string|"MDc6TGljZW5zZW1pdA=="|
|------------ html_url|""|string|""|
|------ forks|""|integer|""|
|------ permissions|""|object|""|
|------------ admin|""|boolean|""|
|------------ pull|""|boolean|""|
|------------ triage|""|boolean|""|
|------------ push|""|boolean|""|
|------------ maintain|""|boolean|""|
|------ owner|"A GitHub user."|object|""|
|------------ name|""|string|""|
|------------ email|""|string|""|
|------------ login|""|string|"octocat"|
|------------ id|""|integer|1|
|------------ node_id|""|string|"MDQ6VXNlcjE="|
|------------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------------ url|""|string|"https://api.github.com/users/octocat"|
|------------ html_url|""|string|"https://github.com/octocat"|
|------------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------------ type|""|string|"User"|
|------------ site_admin|""|boolean|""|
|------------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
|------ private|"Whether the repository is private or public."|boolean|""|
|------ html_url|""|string|"https://github.com/octocat/Hello-World"|
|------ description|""|string|"This your first repo!"|
|------ fork|""|boolean|""|
|------ url|""|string|"https://api.github.com/repos/octocat/Hello-World"|
|------ archive_url|""|string|"http://api.github.com/repos/octocat/Hello-World/{archive_format}{/ref}"|
|------ assignees_url|""|string|"http://api.github.com/repos/octocat/Hello-World/assignees{/user}"|
|------ blobs_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/blobs{/sha}"|
|------ branches_url|""|string|"http://api.github.com/repos/octocat/Hello-World/branches{/branch}"|
|------ collaborators_url|""|string|"http://api.github.com/repos/octocat/Hello-World/collaborators{/collaborator}"|
|------ comments_url|""|string|"http://api.github.com/repos/octocat/Hello-World/comments{/number}"|
|------ commits_url|""|string|"http://api.github.com/repos/octocat/Hello-World/commits{/sha}"|
|------ compare_url|""|string|"http://api.github.com/repos/octocat/Hello-World/compare/{base}...{head}"|
|------ contents_url|""|string|"http://api.github.com/repos/octocat/Hello-World/contents/{+path}"|
|------ contributors_url|""|string|"http://api.github.com/repos/octocat/Hello-World/contributors"|
|------ deployments_url|""|string|"http://api.github.com/repos/octocat/Hello-World/deployments"|
|------ downloads_url|""|string|"http://api.github.com/repos/octocat/Hello-World/downloads"|
|------ events_url|""|string|"http://api.github.com/repos/octocat/Hello-World/events"|
|------ forks_url|""|string|"http://api.github.com/repos/octocat/Hello-World/forks"|
|------ git_commits_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/commits{/sha}"|
|------ git_refs_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/refs{/sha}"|
|------ git_tags_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/tags{/sha}"|
|------ git_url|""|string|"git:github.com/octocat/Hello-World.git"|
|------ issue_comment_url|""|string|"http://api.github.com/repos/octocat/Hello-World/issues/comments{/number}"|
|------ issue_events_url|""|string|"http://api.github.com/repos/octocat/Hello-World/issues/events{/number}"|
|------ issues_url|""|string|"http://api.github.com/repos/octocat/Hello-World/issues{/number}"|
|------ keys_url|""|string|"http://api.github.com/repos/octocat/Hello-World/keys{/key_id}"|
|------ labels_url|""|string|"http://api.github.com/repos/octocat/Hello-World/labels{/name}"|
|------ languages_url|""|string|"http://api.github.com/repos/octocat/Hello-World/languages"|
|------ merges_url|""|string|"http://api.github.com/repos/octocat/Hello-World/merges"|
|------ milestones_url|""|string|"http://api.github.com/repos/octocat/Hello-World/milestones{/number}"|
|------ notifications_url|""|string|"http://api.github.com/repos/octocat/Hello-World/notifications{?since,all,participating}"|
|------ pulls_url|""|string|"http://api.github.com/repos/octocat/Hello-World/pulls{/number}"|
|------ releases_url|""|string|"http://api.github.com/repos/octocat/Hello-World/releases{/id}"|
|------ ssh_url|""|string|"git@github.com:octocat/Hello-World.git"|
|------ stargazers_url|""|string|"http://api.github.com/repos/octocat/Hello-World/stargazers"|
|------ statuses_url|""|string|"http://api.github.com/repos/octocat/Hello-World/statuses/{sha}"|
|------ subscribers_url|""|string|"http://api.github.com/repos/octocat/Hello-World/subscribers"|
|------ subscription_url|""|string|"http://api.github.com/repos/octocat/Hello-World/subscription"|
|------ tags_url|""|string|"http://api.github.com/repos/octocat/Hello-World/tags"|
|------ teams_url|""|string|"http://api.github.com/repos/octocat/Hello-World/teams"|
|------ trees_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/trees{/sha}"|
|------ clone_url|""|string|"https://github.com/octocat/Hello-World.git"|
|------ mirror_url|""|string|"git:git.example.com/octocat/Hello-World"|
|------ hooks_url|""|string|"http://api.github.com/repos/octocat/Hello-World/hooks"|
|------ svn_url|""|string|"https://svn.github.com/octocat/Hello-World"|
|------ homepage|""|string|"https://github.com"|
|------ language|""|string|""|
|------ forks_count|""|integer|9|
|------ stargazers_count|""|integer|80|
|------ watchers_count|""|integer|80|
|------ size|"The size of the repository, in kilobytes. Size is calculated hourly. When a repository is initially created, the size is 0."|integer|108|
|------ default_branch|"The default branch of the repository."|string|"master"|
|------ open_issues_count|""|integer|0|
|------ is_template|"Whether this repository acts as a template that can be used to generate new repositories."|boolean|true|
|------ topics|""|array|""|
|------------ topics|""|string|""|
|------ has_issues|"Whether issues are enabled."|boolean|true|
|------ has_projects|"Whether projects are enabled."|boolean|true|
|------ has_wiki|"Whether the wiki is enabled."|boolean|true|
|------ has_pages|""|boolean|""|
|------ has_downloads|"Whether downloads are enabled."|boolean|true|
|------ has_discussions|"Whether discussions are enabled."|boolean|true|
|------ archived|"Whether the repository is archived."|boolean|""|
|------ disabled|"Returns whether or not this repository disabled."|boolean|""|
|------ visibility|"The repository visibility: public, private, or internal."|string|""|
|------ pushed_at|""|string|"2011-01-26T19:06:43Z"|
|------ created_at|""|string|"2011-01-26T19:01:12Z"|
|------ updated_at|""|string|"2011-01-26T19:14:43Z"|
|------ allow_rebase_merge|"Whether to allow rebase merges for pull requests."|boolean|true|
|------ temp_clone_token|""|string|""|
|------ allow_squash_merge|"Whether to allow squash merges for pull requests."|boolean|true|
|------ allow_auto_merge|"Whether to allow Auto-merge to be used on pull requests."|boolean|false|
|------ delete_branch_on_merge|"Whether to delete head branches when pull requests are merged"|boolean|false|
|------ allow_update_branch|"Whether or not a pull request head branch that is behind its base branch can always be updated even if it is not required to be up to date before merging."|boolean|false|
|------ use_squash_pr_title_as_default|"Whether a squash merge commit can use the pull request title as default. **This property has been deprecated. Please use `squash_merge_commit_title` instead."|boolean|""|
|------ squash_merge_commit_title|"The default value for a squash merge commit title:\n\n- `PR_TITLE` - default to the pull request's title.\n- `COMMIT_OR_PR_TITLE` - default to the commit's title (if only one commit) or the pull request's title (when more than one commit)."|string|""|
|------ squash_merge_commit_message|"The default value for a squash merge commit message:\n\n- `PR_BODY` - default to the pull request's body.\n- `COMMIT_MESSAGES` - default to the branch's commit messages.\n- `BLANK` - default to a blank commit message."|string|""|
|------ merge_commit_title|"The default value for a merge commit title.\n\n- `PR_TITLE` - default to the pull request's title.\n- `MERGE_MESSAGE` - default to the classic title for a merge message (e.g., Merge pull request #123 from branch-name)."|string|""|
|------ merge_commit_message|"The default value for a merge commit message.\n\n- `PR_TITLE` - default to the pull request's title.\n- `PR_BODY` - default to the pull request's body.\n- `BLANK` - default to a blank commit message."|string|""|
|------ allow_merge_commit|"Whether to allow merge commits for pull requests."|boolean|true|
|------ allow_forking|"Whether to allow forking this repo"|boolean|""|
|------ web_commit_signoff_required|"Whether to require contributors to sign off on web-based commits"|boolean|""|
|------ open_issues|""|integer|""|
|------ watchers|""|integer|""|
|------ master_branch|""|string|""|
|------ starred_at|""|string|"\"2020-07-09T00:17:42Z\""|
|------ anonymous_access_enabled|"Whether anonymous git access is enabled for this repository"|boolean|""|
| performed_via_github_app|"GitHub apps are a new way to extend GitHub. They can be installed directly on organizations and user accounts and granted access to specific repositories. They come with granular permissions and built-in webhooks. GitHub apps are first class actors within GitHub."|object|""|
|------ id|"Unique identifier of the GitHub app"|integer|37|
|------ slug|"The slug name of the GitHub app"|string|"probot-owners"|
|------ node_id|""|string|"MDExOkludGVncmF0aW9uMQ=="|
|------ client_id|""|string|"\"Iv1.25b5d1e65ffc4022\""|
|------ owner|"A GitHub user."|object|""|
|------------ name|""|string|""|
|------------ email|""|string|""|
|------------ login|""|string|"octocat"|
|------------ id|""|integer|1|
|------------ node_id|""|string|"MDQ6VXNlcjE="|
|------------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------------ url|""|string|"https://api.github.com/users/octocat"|
|------------ html_url|""|string|"https://github.com/octocat"|
|------------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------------ type|""|string|"User"|
|------------ site_admin|""|boolean|""|
|------------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
|------ name|"The name of the GitHub app"|string|"Probot Owners"|
|------ description|""|string|"The description of the app."|
|------ external_url|""|string|"https://example.com"|
|------ html_url|""|string|"https://github.com/apps/super-ci"|
|------ created_at|""|string|"2017-07-08T16:18:44-04:00"|
|------ updated_at|""|string|"2017-07-08T16:18:44-04:00"|
|------ permissions|"The set of permissions for the GitHub app"|object|""|
|------------ issues|""|string|""|
|------------ checks|""|string|""|
|------------ metadata|""|string|""|
|------------ contents|""|string|""|
|------------ deployments|""|string|""|
|------ events|"The list of events for the GitHub app"|array|"label"|
|------------ events|""|string|""|
|------ installations_count|"The number of installations associated with the GitHub app"|integer|5|
|------ client_secret|""|string|"\"1d4b2097ac622ba702d19de498f005747a8b21d3\""|
|------ webhook_secret|""|string|"\"6fba8f2fc8a7e8f2cca5577eddd82ca7586b3b6b\""|
|------ pem|""|string|"\"-----BEGIN RSA PRIVATE KEY-----\\nMIIEogIBAAKCAQEArYxrNYD/iT5CZVpRJu4rBKmmze3PVmT/gCo2ATUvDvZTPTey\\nxcGJ3vvrJXazKk06pN05TN29o98jrYz4cengG3YGsXPNEpKsIrEl8NhbnxapEnM9\\nJCMRe0P5JcPsfZlX6hmiT7136GRWiGOUba2X9+HKh8QJVLG5rM007TBER9/z9mWm\\nrJuNh+m5l320oBQY/Qq3A7wzdEfZw8qm/mIN0FCeoXH1L6B8xXWaAYBwhTEh6SSn\\nZHlO1Xu1JWDmAvBCi0RO5aRSKM8q9QEkvvHP4yweAtK3N8+aAbZ7ovaDhyGz8r6r\\nzhU1b8Uo0Z2ysf503WqzQgIajr7Fry7/kUwpgQIDAQABAoIBADwJp80Ko1xHPZDy\\nfcCKBDfIuPvkmSW6KumbsLMaQv1aGdHDwwTGv3t0ixSay8CGlxMRtRDyZPib6SvQ\\n6OH/lpfpbMdW2ErkksgtoIKBVrDilfrcAvrNZu7NxRNbhCSvN8q0s4ICecjbbVQh\\nnueSdlA6vGXbW58BHMq68uRbHkP+k+mM9U0mDJ1HMch67wlg5GbayVRt63H7R2+r\\nVxcna7B80J/lCEjIYZznawgiTvp3MSanTglqAYi+m1EcSsP14bJIB9vgaxS79kTu\\noiSo93leJbBvuGo8QEiUqTwMw4tDksmkLsoqNKQ1q9P7LZ9DGcujtPy4EZsamSJT\\ny8OJt0ECgYEA2lxOxJsQk2kI325JgKFjo92mQeUObIvPfSNWUIZQDTjniOI6Gv63\\nGLWVFrZcvQBWjMEQraJA9xjPbblV8PtfO87MiJGLWCHFxmPz2dzoedN+2Coxom8m\\nV95CLz8QUShuao6u/RYcvUaZEoYs5bHcTmy5sBK80JyEmafJPtCQVxMCgYEAy3ar\\nZr3yv4xRPEPMat4rseswmuMooSaK3SKub19WFI5IAtB/e7qR1Rj9JhOGcZz+OQrl\\nT78O2OFYlgOIkJPvRMrPpK5V9lslc7tz1FSh3BZMRGq5jSyD7ETSOQ0c8T2O/s7v\\nbeEPbVbDe4mwvM24XByH0GnWveVxaDl51ABD65sCgYB3ZAspUkOA5egVCh8kNpnd\\nSd6SnuQBE3ySRlT2WEnCwP9Ph6oPgn+oAfiPX4xbRqkL8q/k0BdHQ4h+zNwhk7+h\\nWtPYRAP1Xxnc/F+jGjb+DVaIaKGU18MWPg7f+FI6nampl3Q0KvfxwX0GdNhtio8T\\nTj1E+SnFwh56SRQuxSh2gwKBgHKjlIO5NtNSflsUYFM+hyQiPiqnHzddfhSG+/3o\\nm5nNaSmczJesUYreH5San7/YEy2UxAugvP7aSY2MxB+iGsiJ9WD2kZzTUlDZJ7RV\\nUzWsoqBR+eZfVJ2FUWWvy8TpSG6trh4dFxImNtKejCR1TREpSiTV3Zb1dmahK9GV\\nrK9NAoGAbBxRLoC01xfxCTgt5BDiBcFVh4fp5yYKwavJPLzHSpuDOrrI9jDn1oKN\\nonq5sDU1i391zfQvdrbX4Ova48BN+B7p63FocP/MK5tyyBoT8zQEk2+vWDOw7H/Z\\nu5dTCPxTIsoIwUw1I+7yIxqJzLPFgR2gVBwY1ra/8iAqCj+zeBw=\\n-----END RSA PRIVATE KEY-----\\n\""|
| author_association|"How the author is associated with the repository."|string|"OWNER"|
| reactions|""|object|""|
|------ url|""|string|""|
|------ total_count|""|integer|""|
|------ +1|""|integer|""|
|------ -1|""|integer|""|
|------ laugh|""|integer|""|
|------ confused|""|integer|""|
|------ heart|""|integer|""|
|------ hooray|""|integer|""|
|------ eyes|""|integer|""|
|------ rocket|""|integer|""|

<br/>
<br/>
<br/>

# PR data field description
|data field|description|type|examples|
|:--|:--|:--|:--|
| Pull Request Simple|"Pull Request Simple"|object|""|
| url|""|string|"https://api.github.com/repos/octocat/Hello-World/pulls/1347"|
| id|""|integer|1|
| node_id|""|string|"MDExOlB1bGxSZXF1ZXN0MQ=="|
| html_url|""|string|"https://github.com/octocat/Hello-World/pull/1347"|
| diff_url|""|string|"https://github.com/octocat/Hello-World/pull/1347.diff"|
| patch_url|""|string|"https://github.com/octocat/Hello-World/pull/1347.patch"|
| issue_url|""|string|"https://api.github.com/repos/octocat/Hello-World/issues/1347"|
| commits_url|""|string|"https://api.github.com/repos/octocat/Hello-World/pulls/1347/commits"|
| review_comments_url|""|string|"https://api.github.com/repos/octocat/Hello-World/pulls/1347/comments"|
| review_comment_url|""|string|"https://api.github.com/repos/octocat/Hello-World/pulls/comments{/number}"|
| comments_url|""|string|"https://api.github.com/repos/octocat/Hello-World/issues/1347/comments"|
| statuses_url|""|string|"https://api.github.com/repos/octocat/Hello-World/statuses/6dcb09b5b57875f334f61aebed695e2e4193db5e"|
| number|""|integer|1347|
| state|""|string|"open"|
| locked|""|boolean|true|
| title|""|string|"new-feature"|
| user|"A GitHub user."|object|""|
|------ name|""|string|""|
|------ email|""|string|""|
|------ login|""|string|"octocat"|
|------ id|""|integer|1|
|------ node_id|""|string|"MDQ6VXNlcjE="|
|------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------ url|""|string|"https://api.github.com/users/octocat"|
|------ html_url|""|string|"https://github.com/octocat"|
|------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------ type|""|string|"User"|
|------ site_admin|""|boolean|""|
|------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
| body|""|string|"Please pull these awesome changes"|
| labels|""|array|""|
|------ labels|""|object|""|
|------------ id|""|integer|""|
|------------ node_id|""|string|""|
|------------ url|""|string|""|
|------------ name|""|string|""|
|------------ description|""|string|""|
|------------ color|""|string|""|
|------------ default|""|boolean|""|
| milestone|"A collection of related issues and pull requests."|object|""|
|------ url|""|string|"https://api.github.com/repos/octocat/Hello-World/milestones/1"|
|------ html_url|""|string|"https://github.com/octocat/Hello-World/milestones/v1.0"|
|------ labels_url|""|string|"https://api.github.com/repos/octocat/Hello-World/milestones/1/labels"|
|------ id|""|integer|1002604|
|------ node_id|""|string|"MDk6TWlsZXN0b25lMTAwMjYwNA=="|
|------ number|"The number of the milestone."|integer|42|
|------ state|"The state of the milestone."|string|"open"|
|------ title|"The title of the milestone."|string|"v1.0"|
|------ description|""|string|"Tracking milestone for version 1.0"|
|------ creator|"A GitHub user."|object|""|
|------------ name|""|string|""|
|------------ email|""|string|""|
|------------ login|""|string|"octocat"|
|------------ id|""|integer|1|
|------------ node_id|""|string|"MDQ6VXNlcjE="|
|------------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------------ url|""|string|"https://api.github.com/users/octocat"|
|------------ html_url|""|string|"https://github.com/octocat"|
|------------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------------ type|""|string|"User"|
|------------ site_admin|""|boolean|""|
|------------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
|------ open_issues|""|integer|4|
|------ closed_issues|""|integer|8|
|------ created_at|""|string|"2011-04-10T20:09:31Z"|
|------ updated_at|""|string|"2014-03-03T18:58:10Z"|
|------ closed_at|""|string|"2013-02-12T13:22:01Z"|
|------ due_on|""|string|"2012-10-09T23:39:01Z"|
| active_lock_reason|""|string|"too heated"|
| created_at|""|string|"2011-01-26T19:01:12Z"|
| updated_at|""|string|"2011-01-26T19:01:12Z"|
| closed_at|""|string|"2011-01-26T19:01:12Z"|
| merged_at|""|string|"2011-01-26T19:01:12Z"|
| merge_commit_sha|""|string|"e5bd3914e2e596debea16f433f57875b5b90bcd6"|
| assignee|"A GitHub user."|object|""|
|------ name|""|string|""|
|------ email|""|string|""|
|------ login|""|string|"octocat"|
|------ id|""|integer|1|
|------ node_id|""|string|"MDQ6VXNlcjE="|
|------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------ url|""|string|"https://api.github.com/users/octocat"|
|------ html_url|""|string|"https://github.com/octocat"|
|------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------ type|""|string|"User"|
|------ site_admin|""|boolean|""|
|------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
| assignees|""|array|""|
|------ assignees|"A GitHub user."|object|""|
|------------ name|""|string|""|
|------------ email|""|string|""|
|------------ login|""|string|"octocat"|
|------------ id|""|integer|1|
|------------ node_id|""|string|"MDQ6VXNlcjE="|
|------------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------------ url|""|string|"https://api.github.com/users/octocat"|
|------------ html_url|""|string|"https://github.com/octocat"|
|------------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------------ type|""|string|"User"|
|------------ site_admin|""|boolean|""|
|------------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
| requested_reviewers|""|array|""|
|------ requested_reviewers|"A GitHub user."|object|""|
|------------ name|""|string|""|
|------------ email|""|string|""|
|------------ login|""|string|"octocat"|
|------------ id|""|integer|1|
|------------ node_id|""|string|"MDQ6VXNlcjE="|
|------------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------------ url|""|string|"https://api.github.com/users/octocat"|
|------------ html_url|""|string|"https://github.com/octocat"|
|------------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------------ type|""|string|"User"|
|------------ site_admin|""|boolean|""|
|------------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
| requested_teams|""|array|""|
|------ requested_teams|"Groups of organization members that gives permissions on specified repositories."|object|""|
|------------ id|""|integer|""|
|------------ node_id|""|string|""|
|------------ name|""|string|""|
|------------ slug|""|string|""|
|------------ description|""|string|""|
|------------ privacy|""|string|""|
|------------ notification_setting|""|string|""|
|------------ permission|""|string|""|
|------------ permissions|""|object|""|
|------------------ pull|""|boolean|""|
|------------------ triage|""|boolean|""|
|------------------ push|""|boolean|""|
|------------------ maintain|""|boolean|""|
|------------------ admin|""|boolean|""|
|------------ url|""|string|""|
|------------ html_url|""|string|"https://github.com/orgs/rails/teams/core"|
|------------ members_url|""|string|""|
|------------ repositories_url|""|string|""|
|------------ parent|"Groups of organization members that gives permissions on specified repositories."|object|""|
|------------------ id|"Unique identifier of the team"|integer|1|
|------------------ node_id|""|string|"MDQ6VGVhbTE="|
|------------------ url|"URL for the team"|string|"https://api.github.com/organizations/1/team/1"|
|------------------ members_url|""|string|"https://api.github.com/organizations/1/team/1/members{/member}"|
|------------------ name|"Name of the team"|string|"Justice League"|
|------------------ description|"Description of the team"|string|"A great team."|
|------------------ permission|"Permission that the team will have for its repositories"|string|"admin"|
|------------------ privacy|"The level of privacy this team should have"|string|"closed"|
|------------------ notification_setting|"The notification setting the team has set"|string|"notifications_enabled"|
|------------------ html_url|""|string|"https://github.com/orgs/rails/teams/core"|
|------------------ repositories_url|""|string|"https://api.github.com/organizations/1/team/1/repos"|
|------------------ slug|""|string|"justice-league"|
|------------------ ldap_dn|"Distinguished Name (DN) that team maps to within LDAP environment"|string|"uid=example,ou=users,dc=github,dc=com"|
| head|""|object|""|
|------ label|""|string|""|
|------ ref|""|string|""|
|------ repo|"A repository on GitHub."|object|""|
|------------ id|"Unique identifier of the repository"|integer|42|
|------------ node_id|""|string|"MDEwOlJlcG9zaXRvcnkxMjk2MjY5"|
|------------ name|"The name of the repository."|string|"Team Environment"|
|------------ full_name|""|string|"octocat/Hello-World"|
|------------ license|"License Simple"|object|""|
|------------------ key|""|string|"mit"|
|------------------ name|""|string|"MIT License"|
|------------------ url|""|string|"https://api.github.com/licenses/mit"|
|------------------ spdx_id|""|string|"MIT"|
|------------------ node_id|""|string|"MDc6TGljZW5zZW1pdA=="|
|------------------ html_url|""|string|""|
|------------ forks|""|integer|""|
|------------ permissions|""|object|""|
|------------------ admin|""|boolean|""|
|------------------ pull|""|boolean|""|
|------------------ triage|""|boolean|""|
|------------------ push|""|boolean|""|
|------------------ maintain|""|boolean|""|
|------------ owner|"A GitHub user."|object|""|
|------------------ name|""|string|""|
|------------------ email|""|string|""|
|------------------ login|""|string|"octocat"|
|------------------ id|""|integer|1|
|------------------ node_id|""|string|"MDQ6VXNlcjE="|
|------------------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------------------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------------------ url|""|string|"https://api.github.com/users/octocat"|
|------------------ html_url|""|string|"https://github.com/octocat"|
|------------------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------------------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------------------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------------------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------------------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------------------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------------------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------------------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------------------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------------------ type|""|string|"User"|
|------------------ site_admin|""|boolean|""|
|------------------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
|------------ private|"Whether the repository is private or public."|boolean|""|
|------------ html_url|""|string|"https://github.com/octocat/Hello-World"|
|------------ description|""|string|"This your first repo!"|
|------------ fork|""|boolean|""|
|------------ url|""|string|"https://api.github.com/repos/octocat/Hello-World"|
|------------ archive_url|""|string|"http://api.github.com/repos/octocat/Hello-World/{archive_format}{/ref}"|
|------------ assignees_url|""|string|"http://api.github.com/repos/octocat/Hello-World/assignees{/user}"|
|------------ blobs_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/blobs{/sha}"|
|------------ branches_url|""|string|"http://api.github.com/repos/octocat/Hello-World/branches{/branch}"|
|------------ collaborators_url|""|string|"http://api.github.com/repos/octocat/Hello-World/collaborators{/collaborator}"|
|------------ comments_url|""|string|"http://api.github.com/repos/octocat/Hello-World/comments{/number}"|
|------------ commits_url|""|string|"http://api.github.com/repos/octocat/Hello-World/commits{/sha}"|
|------------ compare_url|""|string|"http://api.github.com/repos/octocat/Hello-World/compare/{base}...{head}"|
|------------ contents_url|""|string|"http://api.github.com/repos/octocat/Hello-World/contents/{+path}"|
|------------ contributors_url|""|string|"http://api.github.com/repos/octocat/Hello-World/contributors"|
|------------ deployments_url|""|string|"http://api.github.com/repos/octocat/Hello-World/deployments"|
|------------ downloads_url|""|string|"http://api.github.com/repos/octocat/Hello-World/downloads"|
|------------ events_url|""|string|"http://api.github.com/repos/octocat/Hello-World/events"|
|------------ forks_url|""|string|"http://api.github.com/repos/octocat/Hello-World/forks"|
|------------ git_commits_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/commits{/sha}"|
|------------ git_refs_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/refs{/sha}"|
|------------ git_tags_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/tags{/sha}"|
|------------ git_url|""|string|"git:github.com/octocat/Hello-World.git"|
|------------ issue_comment_url|""|string|"http://api.github.com/repos/octocat/Hello-World/issues/comments{/number}"|
|------------ issue_events_url|""|string|"http://api.github.com/repos/octocat/Hello-World/issues/events{/number}"|
|------------ issues_url|""|string|"http://api.github.com/repos/octocat/Hello-World/issues{/number}"|
|------------ keys_url|""|string|"http://api.github.com/repos/octocat/Hello-World/keys{/key_id}"|
|------------ labels_url|""|string|"http://api.github.com/repos/octocat/Hello-World/labels{/name}"|
|------------ languages_url|""|string|"http://api.github.com/repos/octocat/Hello-World/languages"|
|------------ merges_url|""|string|"http://api.github.com/repos/octocat/Hello-World/merges"|
|------------ milestones_url|""|string|"http://api.github.com/repos/octocat/Hello-World/milestones{/number}"|
|------------ notifications_url|""|string|"http://api.github.com/repos/octocat/Hello-World/notifications{?since,all,participating}"|
|------------ pulls_url|""|string|"http://api.github.com/repos/octocat/Hello-World/pulls{/number}"|
|------------ releases_url|""|string|"http://api.github.com/repos/octocat/Hello-World/releases{/id}"|
|------------ ssh_url|""|string|"git@github.com:octocat/Hello-World.git"|
|------------ stargazers_url|""|string|"http://api.github.com/repos/octocat/Hello-World/stargazers"|
|------------ statuses_url|""|string|"http://api.github.com/repos/octocat/Hello-World/statuses/{sha}"|
|------------ subscribers_url|""|string|"http://api.github.com/repos/octocat/Hello-World/subscribers"|
|------------ subscription_url|""|string|"http://api.github.com/repos/octocat/Hello-World/subscription"|
|------------ tags_url|""|string|"http://api.github.com/repos/octocat/Hello-World/tags"|
|------------ teams_url|""|string|"http://api.github.com/repos/octocat/Hello-World/teams"|
|------------ trees_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/trees{/sha}"|
|------------ clone_url|""|string|"https://github.com/octocat/Hello-World.git"|
|------------ mirror_url|""|string|"git:git.example.com/octocat/Hello-World"|
|------------ hooks_url|""|string|"http://api.github.com/repos/octocat/Hello-World/hooks"|
|------------ svn_url|""|string|"https://svn.github.com/octocat/Hello-World"|
|------------ homepage|""|string|"https://github.com"|
|------------ language|""|string|""|
|------------ forks_count|""|integer|9|
|------------ stargazers_count|""|integer|80|
|------------ watchers_count|""|integer|80|
|------------ size|"The size of the repository, in kilobytes. Size is calculated hourly. When a repository is initially created, the size is 0."|integer|108|
|------------ default_branch|"The default branch of the repository."|string|"master"|
|------------ open_issues_count|""|integer|0|
|------------ is_template|"Whether this repository acts as a template that can be used to generate new repositories."|boolean|true|
|------------ topics|""|array|""|
|------------------ topics|""|string|""|
|------------ has_issues|"Whether issues are enabled."|boolean|true|
|------------ has_projects|"Whether projects are enabled."|boolean|true|
|------------ has_wiki|"Whether the wiki is enabled."|boolean|true|
|------------ has_pages|""|boolean|""|
|------------ has_downloads|"Whether downloads are enabled."|boolean|true|
|------------ has_discussions|"Whether discussions are enabled."|boolean|true|
|------------ archived|"Whether the repository is archived."|boolean|""|
|------------ disabled|"Returns whether or not this repository disabled."|boolean|""|
|------------ visibility|"The repository visibility: public, private, or internal."|string|""|
|------------ pushed_at|""|string|"2011-01-26T19:06:43Z"|
|------------ created_at|""|string|"2011-01-26T19:01:12Z"|
|------------ updated_at|""|string|"2011-01-26T19:14:43Z"|
|------------ allow_rebase_merge|"Whether to allow rebase merges for pull requests."|boolean|true|
|------------ temp_clone_token|""|string|""|
|------------ allow_squash_merge|"Whether to allow squash merges for pull requests."|boolean|true|
|------------ allow_auto_merge|"Whether to allow Auto-merge to be used on pull requests."|boolean|false|
|------------ delete_branch_on_merge|"Whether to delete head branches when pull requests are merged"|boolean|false|
|------------ allow_update_branch|"Whether or not a pull request head branch that is behind its base branch can always be updated even if it is not required to be up to date before merging."|boolean|false|
|------------ use_squash_pr_title_as_default|"Whether a squash merge commit can use the pull request title as default. **This property has been deprecated. Please use `squash_merge_commit_title` instead."|boolean|""|
|------------ squash_merge_commit_title|"The default value for a squash merge commit title:\n\n- `PR_TITLE` - default to the pull request's title.\n- `COMMIT_OR_PR_TITLE` - default to the commit's title (if only one commit) or the pull request's title (when more than one commit)."|string|""|
|------------ squash_merge_commit_message|"The default value for a squash merge commit message:\n\n- `PR_BODY` - default to the pull request's body.\n- `COMMIT_MESSAGES` - default to the branch's commit messages.\n- `BLANK` - default to a blank commit message."|string|""|
|------------ merge_commit_title|"The default value for a merge commit title.\n\n- `PR_TITLE` - default to the pull request's title.\n- `MERGE_MESSAGE` - default to the classic title for a merge message (e.g., Merge pull request #123 from branch-name)."|string|""|
|------------ merge_commit_message|"The default value for a merge commit message.\n\n- `PR_TITLE` - default to the pull request's title.\n- `PR_BODY` - default to the pull request's body.\n- `BLANK` - default to a blank commit message."|string|""|
|------------ allow_merge_commit|"Whether to allow merge commits for pull requests."|boolean|true|
|------------ allow_forking|"Whether to allow forking this repo"|boolean|""|
|------------ web_commit_signoff_required|"Whether to require contributors to sign off on web-based commits"|boolean|""|
|------------ open_issues|""|integer|""|
|------------ watchers|""|integer|""|
|------------ master_branch|""|string|""|
|------------ starred_at|""|string|"\"2020-07-09T00:17:42Z\""|
|------------ anonymous_access_enabled|"Whether anonymous git access is enabled for this repository"|boolean|""|
|------ sha|""|string|""|
|------ user|"A GitHub user."|object|""|
|------------ name|""|string|""|
|------------ email|""|string|""|
|------------ login|""|string|"octocat"|
|------------ id|""|integer|1|
|------------ node_id|""|string|"MDQ6VXNlcjE="|
|------------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------------ url|""|string|"https://api.github.com/users/octocat"|
|------------ html_url|""|string|"https://github.com/octocat"|
|------------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------------ type|""|string|"User"|
|------------ site_admin|""|boolean|""|
|------------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
| base|""|object|""|
|------ label|""|string|""|
|------ ref|""|string|""|
|------ repo|"A repository on GitHub."|object|""|
|------------ id|"Unique identifier of the repository"|integer|42|
|------------ node_id|""|string|"MDEwOlJlcG9zaXRvcnkxMjk2MjY5"|
|------------ name|"The name of the repository."|string|"Team Environment"|
|------------ full_name|""|string|"octocat/Hello-World"|
|------------ license|"License Simple"|object|""|
|------------------ key|""|string|"mit"|
|------------------ name|""|string|"MIT License"|
|------------------ url|""|string|"https://api.github.com/licenses/mit"|
|------------------ spdx_id|""|string|"MIT"|
|------------------ node_id|""|string|"MDc6TGljZW5zZW1pdA=="|
|------------------ html_url|""|string|""|
|------------ forks|""|integer|""|
|------------ permissions|""|object|""|
|------------------ admin|""|boolean|""|
|------------------ pull|""|boolean|""|
|------------------ triage|""|boolean|""|
|------------------ push|""|boolean|""|
|------------------ maintain|""|boolean|""|
|------------ owner|"A GitHub user."|object|""|
|------------------ name|""|string|""|
|------------------ email|""|string|""|
|------------------ login|""|string|"octocat"|
|------------------ id|""|integer|1|
|------------------ node_id|""|string|"MDQ6VXNlcjE="|
|------------------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------------------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------------------ url|""|string|"https://api.github.com/users/octocat"|
|------------------ html_url|""|string|"https://github.com/octocat"|
|------------------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------------------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------------------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------------------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------------------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------------------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------------------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------------------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------------------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------------------ type|""|string|"User"|
|------------------ site_admin|""|boolean|""|
|------------------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
|------------ private|"Whether the repository is private or public."|boolean|""|
|------------ html_url|""|string|"https://github.com/octocat/Hello-World"|
|------------ description|""|string|"This your first repo!"|
|------------ fork|""|boolean|""|
|------------ url|""|string|"https://api.github.com/repos/octocat/Hello-World"|
|------------ archive_url|""|string|"http://api.github.com/repos/octocat/Hello-World/{archive_format}{/ref}"|
|------------ assignees_url|""|string|"http://api.github.com/repos/octocat/Hello-World/assignees{/user}"|
|------------ blobs_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/blobs{/sha}"|
|------------ branches_url|""|string|"http://api.github.com/repos/octocat/Hello-World/branches{/branch}"|
|------------ collaborators_url|""|string|"http://api.github.com/repos/octocat/Hello-World/collaborators{/collaborator}"|
|------------ comments_url|""|string|"http://api.github.com/repos/octocat/Hello-World/comments{/number}"|
|------------ commits_url|""|string|"http://api.github.com/repos/octocat/Hello-World/commits{/sha}"|
|------------ compare_url|""|string|"http://api.github.com/repos/octocat/Hello-World/compare/{base}...{head}"|
|------------ contents_url|""|string|"http://api.github.com/repos/octocat/Hello-World/contents/{+path}"|
|------------ contributors_url|""|string|"http://api.github.com/repos/octocat/Hello-World/contributors"|
|------------ deployments_url|""|string|"http://api.github.com/repos/octocat/Hello-World/deployments"|
|------------ downloads_url|""|string|"http://api.github.com/repos/octocat/Hello-World/downloads"|
|------------ events_url|""|string|"http://api.github.com/repos/octocat/Hello-World/events"|
|------------ forks_url|""|string|"http://api.github.com/repos/octocat/Hello-World/forks"|
|------------ git_commits_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/commits{/sha}"|
|------------ git_refs_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/refs{/sha}"|
|------------ git_tags_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/tags{/sha}"|
|------------ git_url|""|string|"git:github.com/octocat/Hello-World.git"|
|------------ issue_comment_url|""|string|"http://api.github.com/repos/octocat/Hello-World/issues/comments{/number}"|
|------------ issue_events_url|""|string|"http://api.github.com/repos/octocat/Hello-World/issues/events{/number}"|
|------------ issues_url|""|string|"http://api.github.com/repos/octocat/Hello-World/issues{/number}"|
|------------ keys_url|""|string|"http://api.github.com/repos/octocat/Hello-World/keys{/key_id}"|
|------------ labels_url|""|string|"http://api.github.com/repos/octocat/Hello-World/labels{/name}"|
|------------ languages_url|""|string|"http://api.github.com/repos/octocat/Hello-World/languages"|
|------------ merges_url|""|string|"http://api.github.com/repos/octocat/Hello-World/merges"|
|------------ milestones_url|""|string|"http://api.github.com/repos/octocat/Hello-World/milestones{/number}"|
|------------ notifications_url|""|string|"http://api.github.com/repos/octocat/Hello-World/notifications{?since,all,participating}"|
|------------ pulls_url|""|string|"http://api.github.com/repos/octocat/Hello-World/pulls{/number}"|
|------------ releases_url|""|string|"http://api.github.com/repos/octocat/Hello-World/releases{/id}"|
|------------ ssh_url|""|string|"git@github.com:octocat/Hello-World.git"|
|------------ stargazers_url|""|string|"http://api.github.com/repos/octocat/Hello-World/stargazers"|
|------------ statuses_url|""|string|"http://api.github.com/repos/octocat/Hello-World/statuses/{sha}"|
|------------ subscribers_url|""|string|"http://api.github.com/repos/octocat/Hello-World/subscribers"|
|------------ subscription_url|""|string|"http://api.github.com/repos/octocat/Hello-World/subscription"|
|------------ tags_url|""|string|"http://api.github.com/repos/octocat/Hello-World/tags"|
|------------ teams_url|""|string|"http://api.github.com/repos/octocat/Hello-World/teams"|
|------------ trees_url|""|string|"http://api.github.com/repos/octocat/Hello-World/git/trees{/sha}"|
|------------ clone_url|""|string|"https://github.com/octocat/Hello-World.git"|
|------------ mirror_url|""|string|"git:git.example.com/octocat/Hello-World"|
|------------ hooks_url|""|string|"http://api.github.com/repos/octocat/Hello-World/hooks"|
|------------ svn_url|""|string|"https://svn.github.com/octocat/Hello-World"|
|------------ homepage|""|string|"https://github.com"|
|------------ language|""|string|""|
|------------ forks_count|""|integer|9|
|------------ stargazers_count|""|integer|80|
|------------ watchers_count|""|integer|80|
|------------ size|"The size of the repository, in kilobytes. Size is calculated hourly. When a repository is initially created, the size is 0."|integer|108|
|------------ default_branch|"The default branch of the repository."|string|"master"|
|------------ open_issues_count|""|integer|0|
|------------ is_template|"Whether this repository acts as a template that can be used to generate new repositories."|boolean|true|
|------------ topics|""|array|""|
|------------------ topics|""|string|""|
|------------ has_issues|"Whether issues are enabled."|boolean|true|
|------------ has_projects|"Whether projects are enabled."|boolean|true|
|------------ has_wiki|"Whether the wiki is enabled."|boolean|true|
|------------ has_pages|""|boolean|""|
|------------ has_downloads|"Whether downloads are enabled."|boolean|true|
|------------ has_discussions|"Whether discussions are enabled."|boolean|true|
|------------ archived|"Whether the repository is archived."|boolean|""|
|------------ disabled|"Returns whether or not this repository disabled."|boolean|""|
|------------ visibility|"The repository visibility: public, private, or internal."|string|""|
|------------ pushed_at|""|string|"2011-01-26T19:06:43Z"|
|------------ created_at|""|string|"2011-01-26T19:01:12Z"|
|------------ updated_at|""|string|"2011-01-26T19:14:43Z"|
|------------ allow_rebase_merge|"Whether to allow rebase merges for pull requests."|boolean|true|
|------------ temp_clone_token|""|string|""|
|------------ allow_squash_merge|"Whether to allow squash merges for pull requests."|boolean|true|
|------------ allow_auto_merge|"Whether to allow Auto-merge to be used on pull requests."|boolean|false|
|------------ delete_branch_on_merge|"Whether to delete head branches when pull requests are merged"|boolean|false|
|------------ allow_update_branch|"Whether or not a pull request head branch that is behind its base branch can always be updated even if it is not required to be up to date before merging."|boolean|false|
|------------ use_squash_pr_title_as_default|"Whether a squash merge commit can use the pull request title as default. **This property has been deprecated. Please use `squash_merge_commit_title` instead."|boolean|""|
|------------ squash_merge_commit_title|"The default value for a squash merge commit title:\n\n- `PR_TITLE` - default to the pull request's title.\n- `COMMIT_OR_PR_TITLE` - default to the commit's title (if only one commit) or the pull request's title (when more than one commit)."|string|""|
|------------ squash_merge_commit_message|"The default value for a squash merge commit message:\n\n- `PR_BODY` - default to the pull request's body.\n- `COMMIT_MESSAGES` - default to the branch's commit messages.\n- `BLANK` - default to a blank commit message."|string|""|
|------------ merge_commit_title|"The default value for a merge commit title.\n\n- `PR_TITLE` - default to the pull request's title.\n- `MERGE_MESSAGE` - default to the classic title for a merge message (e.g., Merge pull request #123 from branch-name)."|string|""|
|------------ merge_commit_message|"The default value for a merge commit message.\n\n- `PR_TITLE` - default to the pull request's title.\n- `PR_BODY` - default to the pull request's body.\n- `BLANK` - default to a blank commit message."|string|""|
|------------ allow_merge_commit|"Whether to allow merge commits for pull requests."|boolean|true|
|------------ allow_forking|"Whether to allow forking this repo"|boolean|""|
|------------ web_commit_signoff_required|"Whether to require contributors to sign off on web-based commits"|boolean|""|
|------------ open_issues|""|integer|""|
|------------ watchers|""|integer|""|
|------------ master_branch|""|string|""|
|------------ starred_at|""|string|"\"2020-07-09T00:17:42Z\""|
|------------ anonymous_access_enabled|"Whether anonymous git access is enabled for this repository"|boolean|""|
|------ sha|""|string|""|
|------ user|"A GitHub user."|object|""|
|------------ name|""|string|""|
|------------ email|""|string|""|
|------------ login|""|string|"octocat"|
|------------ id|""|integer|1|
|------------ node_id|""|string|"MDQ6VXNlcjE="|
|------------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------------ url|""|string|"https://api.github.com/users/octocat"|
|------------ html_url|""|string|"https://github.com/octocat"|
|------------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------------ type|""|string|"User"|
|------------ site_admin|""|boolean|""|
|------------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
| _links|""|object|""|
|------ comments|"Hypermedia Link"|object|""|
|------------ href|""|string|""|
|------ commits|"Hypermedia Link"|object|""|
|------------ href|""|string|""|
|------ statuses|"Hypermedia Link"|object|""|
|------------ href|""|string|""|
|------ html|"Hypermedia Link"|object|""|
|------------ href|""|string|""|
|------ issue|"Hypermedia Link"|object|""|
|------------ href|""|string|""|
|------ review_comments|"Hypermedia Link"|object|""|
|------------ href|""|string|""|
|------ review_comment|"Hypermedia Link"|object|""|
|------------ href|""|string|""|
|------ self|"Hypermedia Link"|object|""|
|------------ href|""|string|""|
| author_association|"How the author is associated with the repository."|string|"OWNER"|
| auto_merge|"The status of auto merging a pull request."|object|""|
|------ enabled_by|"A GitHub user."|object|""|
|------------ name|""|string|""|
|------------ email|""|string|""|
|------------ login|""|string|"octocat"|
|------------ id|""|integer|1|
|------------ node_id|""|string|"MDQ6VXNlcjE="|
|------------ avatar_url|""|string|"https://github.com/images/error/octocat_happy.gif"|
|------------ gravatar_id|""|string|"41d064eb2195891e12d0413f63227ea7"|
|------------ url|""|string|"https://api.github.com/users/octocat"|
|------------ html_url|""|string|"https://github.com/octocat"|
|------------ followers_url|""|string|"https://api.github.com/users/octocat/followers"|
|------------ following_url|""|string|"https://api.github.com/users/octocat/following{/other_user}"|
|------------ gists_url|""|string|"https://api.github.com/users/octocat/gists{/gist_id}"|
|------------ starred_url|""|string|"https://api.github.com/users/octocat/starred{/owner}{/repo}"|
|------------ subscriptions_url|""|string|"https://api.github.com/users/octocat/subscriptions"|
|------------ organizations_url|""|string|"https://api.github.com/users/octocat/orgs"|
|------------ repos_url|""|string|"https://api.github.com/users/octocat/repos"|
|------------ events_url|""|string|"https://api.github.com/users/octocat/events{/privacy}"|
|------------ received_events_url|""|string|"https://api.github.com/users/octocat/received_events"|
|------------ type|""|string|"User"|
|------------ site_admin|""|boolean|""|
|------------ starred_at|""|string|"\"2020-07-09T00:17:55Z\""|
|------ merge_method|"The merge method to use."|string|""|
|------ commit_title|"Title for the merge commit message."|string|""|
|------ commit_message|"Commit message for the merge commit."|string|""|
| draft|"Indicates whether or not the pull request is a draft."|boolean|false|
