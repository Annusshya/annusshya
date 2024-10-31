# Moscow GitHub Users and Repositories Analysis

- We scraped data from GitHub using the GitHub API, focusing on users in Moscow with over 50 followers.
- The most interesting finding was that many developers had significantly more stars on their repositories than watchers.
- For developers, maintaining project wikis and using proper licensing could attract more collaborators and users to their repositories.

## Files:

- `users.csv`: Contains details about each user.
- `repositories.csv`: Contains information about their public repositories.

## Process:

The data was collected using Python and the GitHub API. The users’ data was filtered for location and follower count, and repositories were extracted for each user.

## Results:

After gathering the data, we found that most Moscow-based developers favor specific languages like JavaScript and Python. A surprising fact was that only a few repositories utilized GitHub's project management features.

## Recommendations:

Developers should consider adding GitHub project boards and wikis to increase engagement. Licenses were also missing in some repositories, which can be a deterrent to potential collaborators.
