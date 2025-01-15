```toml
name = 'update'
method = 'PUT'
url = 'http://localhost:85/api/posts/2'
sortWeight = 2000000
id = '550c2dc1-f2b7-4263-b7fd-a70cdbda5c6f'

[[headers]]
key = 'Accept'
value = 'application/json'

[body]
type = 'JSON'
raw = '''
{
  "title": "Post 2 Update",
  "body": "this is the post body"
}'''
```
