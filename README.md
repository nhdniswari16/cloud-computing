
# BinBuddy 

This project aims to develop a mobile application that classifies recyclable household waste in real-time, utilizing a cloud-based Convolutional Neural Network (CNN) model powered by TensorFlow. Aligned with the theme of "Sustainable Futures," this application promotes environmental sustainability by simplifying waste sorting and fostering responsible waste management.




## API Documentation

### Enpoint Usage
#### Base Url : 

#### Get all items

```http
  POST /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.

