# Contests API

## List public contests

### Request

```
GET /contest/list?_contentOnly=1
```

### Response Type

```
application/json: DataResponse<ContestListData>
```

## Get contest

### Request

```
GET /contest/:id?_contentOnly=1
```

### Response Type

```
application/json: DataResponse<ContestData>
```