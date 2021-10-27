# Problem Statement 1- 

Problem – To find out which show the person watched first after buying an OTT’s subscription plan.



![Q1 A](https://user-images.githubusercontent.com/90283295/139030552-d731f8e9-75ad-408c-8d6e-c2741e61b6fb.JPG)


![Output](https://user-images.githubusercontent.com/90283295/139030579-e7b67550-4319-41fb-98cf-831f4c2be1dc.JPG)




Solution – We have used lag to find out what the first entry is on the basis of username for the person after they have bought the subscription.
We created a new variable called 1st_show, we denoted the value of 1 against it, when it was the first entry for a distinct user_id after purchasing the subscription.
Then we recalled our final solution by asking SQL to return, the show column as first show and user_id where the 1st_show variable had the value of 1.
Hence, we get our desired result.


![Answer](https://user-images.githubusercontent.com/90283295/139030590-70b9324f-3a46-4066-885a-359458601fee.JPG)



------------------------------------------------------------------------------------------------------------------------------------------------------------
