# GitHub Users in Zurich

This repository contains data about GitHub users in Zurich with over 50 followers and their repositories.

## Files

1. `users.csv`: Contains information about 482 GitHub users in Zurich with over 50 followers
2. `repositories.csv`: Contains information about 29511 public repositories from these users
3. `gitscrap(fetch).py`: Python script used to collect this data

## Data Collection

- Start → GitHub API Request: The process begins with a request to the GitHub API.
- GitHub API Request → Query Users in Zurich with >50 Followers: Users are queried based on the city (Zurich) and follower count (greater than 50).
- Query Users → Retrieve Public Repos for Each User: Public repositories are retrieved for each identified user.
- Retrieve Public Repos → Up to 482 Most Recent Repos per User: The process limits the data to the 482 most recent repositories per user.
- Up to 482 Most Recent Repos → Export Data: The collected data is exported to CSV format.
- Export Data → users.csv, repositories.csv, and gitscrap.py as Final Outputs

## Recommendations for Developers

#### 1. Documentation Enhancement
- Enable wiki features for comprehensive documentation
- Maintain up-to-date API documentation
- Create detailed setup guides
- Document architectural decisions

#### 2. Project Management
- Implement structured project boards
- Use milestone tracking effectively
- Enable automated task assignments
- Regular sprint planning and reviews

#### 3. Collaboration Tools
- Utilize GitHub Discussions for community engagement
- Enable issue templates
- Implement pull request templates
- Set up automated workflow tools


