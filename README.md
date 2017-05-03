# Checklist PCPart System
-------------------------------------------

### Dummy Data

``` js
{
  websiteId: String,
  link: String,
  price: Number
}
```

### User Class

```js
{
  username: String,
  password: String,
  profiile: UserProfile,
}
```

### UserProfile Class

```js
{
  firstname: String,
  lastname: String,
  userType: Number, // 0 - Admin, 1 - User
}
```

