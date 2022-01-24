# Instagram Analysis on 1100 Instagram Users from [Kaggle](https://www.kaggle.com/itokianarafidinarivo/1100-instagram-users-datetime-posts-data) 
Result:

1. People who get likes the most
<img width="197" alt="Screen Shot 2022-01-24 at 12 49 40" src="https://user-images.githubusercontent.com/3623363/150726159-8c99fe30-8808-40a5-a1dc-ef5f7eab5cb7.png">
Distribution of the likes in the data
<img width="164" alt="Screen Shot 2022-01-24 at 12 50 40" src="https://user-images.githubusercontent.com/3623363/150726186-1331b569-8bef-4822-86d0-770826228485.png"> <br/>

2. People who post the most <br/>
Most people 64% (700 from 1089 users) send 200 posts which is the maximum post per user in this data <br/>
- Is the people who send many posts also get many likes?<br/>
People who got likes more likes than average likes that people get is 136 of 1089 people<br/>
3. On what month people usually send post the most?<br/>
January is month when people send post the most<br/>
4. Is good for posting post sequential? Based on like score<br/>
Likes score will decrease until 8% if the user send post sequentially The idea is sorting data based on user uuid and date posted, I want to compare the data today and yesterday, is there any increment in the like score. If there is an increment, then I labelled it to true, vice versa. To drive conclusion, I calculate how much true (like score increases), and how much the false I got the false is more than the true ones<br/>
The next question is how much is the impact of sending posts sequentially? To answer that question, I make calculation on:<br/>
(avg Likes Score value of sequential post - avg Likes Score value of non sequential post) / avg Likes Score value of non sequential post <br/> 
- Can Likes Score derive from Likes?<br/> 
Likes Score didn't related to likes and days passed for post

