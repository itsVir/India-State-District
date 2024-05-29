
# India States and it's Districts 
Data Updated at 29 May, 2024


## API Reference

#### Get all states

```
    GET /api/states
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get districts of a state

```
    GET /api/states/${state}/districts
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `state`   | `string` | **Required**.Name of the state    |

#### Get towns of a district

```
      GET /api/states/${state}/districts/${district}/towns
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `state`   | `string` | **Required**.Name of the state    |
| `district`| `string` | **Required**.Name of the district |


