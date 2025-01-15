```toml
name = 'create'
method = 'POST'
url = 'http://localhost:85/api/posts'
sortWeight = 4000000
id = '0ce3bb82-3aa7-467e-a5b8-263cdc59c8ca'

[[headers]]
key = 'Accept'
value = 'application/json'

[body]
type = 'JSON'
raw = '''
{
//  "title": "Post 1",
  "body": "this is the post body"
}'''
```
