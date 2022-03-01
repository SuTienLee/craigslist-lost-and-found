# craigslist-lost-and-found
### Craigslist’s Lost and Found automatic labeling with python

This project was contributed by MS Business Analytcis and Information Management students at Purdue University:
> Kai-Duan Chang, Li-Ci Chuang, Meghan Harris, Su-Tien Lee, Yen-Tzu Huang, Yi-Hsuan Hsu (In alphabetical order)

This project dealt with an issue in Craigslist. By automatically labeling the ads as lost or found within the“lost+found” section, we could ensure posts are accurately labeled and save the users' time. We created the topic modeling and Latent Dirichlet Allocation (LDA) to extract the topics of each post and tried to figure out what are the most mentioned topics in the lost&found section of each location. Last but not least, we did the image recognition to automatically predict the attributes of the images. These would further improve user and advertising experience. 

**Goal**: To provide a search for ads via lost or found and to identify images based on keywords and keyword topics based on titles and descriptions. 

**Flow**: We first scraped data from Craigslist, from both Los Angelos (LA) and West Lafayette (WL), preprocessed and analyzed data, and built models to automatically label posts into “lost” or “found”. Topic LDA was also based on the scraped files. The image recognition was done by first building the VGG model, prepare and feed the images, and at last predict the labels.
