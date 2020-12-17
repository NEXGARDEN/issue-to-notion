# issue-to-notion
Modified version for Nexgarden

## Usage

Create `.github/workflows/issue-to-notion.yml` in your repository.
And copy&paste following, and edit appropriately.

| Input Key | Required | Default value | Description |
|:-----:|:-----:|:-----:|-----|
| NOTION_TOKEN | O | X | Auth token called token_v2 from cookie in your browser. Put it your repository secret, and name it NOTION_TOKEN(Recommended) |
| DATABASE_URL | O | X | The url of the database you are trying to access |
| PROPERTY_NAME | X | status | Name of your PROPERTY which will be changed |
| STATE_OPEN | X | open | Your OPEN state name |
| STATE_CLOSED | X | closed | Your CLOSED state name |

## Dependency 
This action uses  
+ [notion-py](https://github.com/jamalex/notion-py)   
+ [md2notion](https://github.com/Cobertos/md2notion)

## Reference
