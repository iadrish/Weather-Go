 # Weather Go  
![Screenshot 2023-01-05 131657](https://user-images.githubusercontent.com/88700100/210728264-74157b35-f858-4d3d-ad4c-e9e6db255bb3.png)


A simple and responsive Weather web app built using HTML and Javascript. 
It utilises 

Weather by API
Ninjas(A RAPID API) to fetch 

(Max/Min)Temperature,
 
 Weather, 
 
 Humidity 

 Wind Speed 

Cloud PCT details.

## Authors

- [@iadrish](https://github.com/iadrishe)


## Acknowledgements

 - [HTML resources](https://www.w3schools.com/html/)
 - [Javascript resources](https://www.w3schools.com/js/default.asp)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
 - [Readme Generator](https://www.makeareadme.com/)

## API Reference

#### Get all items
#### Get item

```http
  GET /api/items/${id}
```
#### Header Parameters
```http
  GET url: 'https://weather-by-api-ninjas.p.rapidapi.com/v1/weather',
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `X-RapidAPI-Key` | `enum` | **Required**.  5ee3fc58aamshb8d18718b9b3b4ep1bef1bjsn2f346e |



| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `X-RapidAPI-Host`      | `string` | **Required**. weather-by-api-ninjas.p.rapidapi.com |



| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Lat`      | `number` | Latitude of Desired Location;If Latitude provided Longitude also required |


| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Lon`      | `string` | Longitude of Desired Location;If Longitude provided Latitude also required |


## Deployment

To deploy this project run

```bash
  npm run deploy
```


## Demo

Deployment is Live on: https://iadrish.github.io/Weather-Go/



## Screenshots

![Howrah jpg](https://user-images.githubusercontent.com/88700100/210727751-4c8fa72c-0281-4dc3-a882-7653dc024edf.png)



![Shantiniketan jpg](https://user-images.githubusercontent.com/88700100/210727818-e26f1f4f-42d4-4883-8cef-dbec9590d48c.png)

