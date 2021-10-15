# github-api-python

### GET /users/defunkt
`$ curl https://api.github.com/users/jsidberry`

`$ curl -i https://api.github.com/users/jsidberry`


Use a -u flag to set your username:

`$ curl -i -u jsidberry https://api.github.com/users/jsidberry`
or with the token (best to use env_vars)
`$ curl -i -u "jsidberry:$token" https://api.github.com/users/jsidberry`

List Repos
`$ curl -i https://api.github.com/users/jsidberry/repos`