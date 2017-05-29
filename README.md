# rails5

特にオプションを付けずにフルインストールする

```
$ rails new . -f
```

# scaffold full

## simple

```
$ rails generate scaffold AdminUser name:string mail:string
```

```
$ rails routes

         Prefix Verb   URI Pattern                     Controller#Action
    admin_users GET    /admin_users(.:format)          admin_users#index
                POST   /admin_users(.:format)          admin_users#create
 new_admin_user GET    /admin_users/new(.:format)      admin_users#new
edit_admin_user GET    /admin_users/:id/edit(.:format) admin_users#edit
     admin_user GET    /admin_users/:id(.:format)      admin_users#show
                PATCH  /admin_users/:id(.:format)      admin_users#update
                PUT    /admin_users/:id(.:format)      admin_users#update
                DELETE /admin_users/:id(.:format)      admin_users#destroy
```
