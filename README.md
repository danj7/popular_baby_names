# Popular Baby Names
In this project I will analyze trends in baby names for the United States from 1880 to 2018. The data is freely available from the Popular Baby Names datasets page located at https://www.ssa.gov/oact/babynames/limits.html.

## Names, comings and goings

We often have the notion of an _old-sounding_ name, maybe because it's a name that reminds us of an elder relative or a historical figure. We also notice the reverse, that there are _modern-sounding_, newer, that may have recently come into fashion. I will explore these notions a little bit in this project, starting from the comings and goings of names.

First, I want to explore the changes year to year of the most popular names. To do this visually, I will use a word clouds, one for male names and another for female names.

Top 100 Female Names per Year    |  Top 100 Male Names per Year
:-------------------------:|:-------------------------:
![top100Fnames_4x3](https://user-images.githubusercontent.com/13749006/69764908-efae2280-113f-11ea-82f6-40cb939fd186.gif)  | ![top100Mnames_4x3](https://user-images.githubusercontent.com/13749006/69764934-048ab600-1140-11ea-8165-3622a92e6736.gif)


From them we notice the following names going out of fashion, for example
* Male: William, John, James
* Female: Mary, Anna, Helen

And some names coming into fashion like
* Male: Jacob, Michael, Noah
* Female: Jennifer, Emily, Olivia

The historical popularity of this names can be obtained and plotted. For example, for the name 'Victor', the historical popularity in total number of registrations can be seen on the graph on the left while the percentage of total names registered per year can be seen on the right graph.

![Historical popularity for the name Victor](https://user-images.githubusercontent.com/13749006/69765545-57656d00-1142-11ea-831f-f278cb634fdc.png)

We can find names that have come in and out of fashion using a mask to weigh the popularity numbers and obtain a score. The names with a higher score would conform better with the pattern (the details are in the Jupyter Notebook `Baby Names - Names coming and going`. The two masks used are shown below:

Mask for names going out | Mask for names coming in
:---:|:---:
![going out](https://user-images.githubusercontent.com/13749006/69767263-6b609d00-1149-11ea-8ae8-5150988762d5.png) | ![coming in](https://user-images.githubusercontent.com/13749006/69767280-7b787c80-1149-11ea-9242-3405744d6417.png)

With this tool we can find, for example, top five female names who became less popular:

![image](https://user-images.githubusercontent.com/13749006/69767342-c7c3bc80-1149-11ea-8483-50b08aab1001.png)

and the top five male names that increased in popularity:

![image](https://user-images.githubusercontent.com/13749006/69767394-fa6db500-1149-11ea-8900-41b69c031017.png)

## Names and media

Media such as books and movies are incredibly influential in all our lives. They do not solely entertain but can also change how we think and do things. One of those things is choosing your baby's name. Here are various examples of how movies and books affected the popularity of various names:

### I Love Lucy
'Lucy' is not an uncommon name but up until the 1950s there must've not been many Desiderios, or Desi, living in the US. Such was the name of the actor who played Ricky Ricardo in the show. The popularity and year the show was released can be seen in the following graph.

Popularity of 'Desi' | I Love Lucy
:---:|:---:
 ![Popularity of Desi](https://user-images.githubusercontent.com/13749006/69770589-994cde00-1157-11ea-98ca-0a5979d6775c.png) | ![I Love Lucy](https://user-images.githubusercontent.com/13749006/69770569-863a0e00-1157-11ea-92c2-c9d10c1495b5.png)

 ### The Lion King
 Even though the characters were animals the names still became somewhat popular. Here we show the popularity of some of the names.

 Popularity of 'Mufasa' and 'Simba' | Popularity of 'Nala' | The Lion King
 :---:|:---:|:---:
![Mufasa and Simba](https://user-images.githubusercontent.com/13749006/69771059-660b4e80-1159-11ea-86fe-c90b0713e344.png) | ![Nala](https://user-images.githubusercontent.com/13749006/69771073-74596a80-1159-11ea-8852-ce522d2fd6a0.png) | ![The Lion King](https://user-images.githubusercontent.com/13749006/69771091-8f2bdf00-1159-11ea-8718-4ac722e0b4e1.png)

### Mulan
This was a very influential and popular movie, perhaps for girls especially. Many parents must've also been inspired by the movie to name their girls like the protagonist.

 Popularity of 'Mulan' | Mulan
 :---:|:---:
 ![Mulan](https://user-images.githubusercontent.com/13749006/69770908-c221a300-1158-11ea-8d8f-ec7f23674e6c.png) | ![Mulan](https://user-images.githubusercontent.com/13749006/69771114-a7036300-1159-11ea-9962-c2330dfd60d3.png)

### Game of Thrones
This show was incredibly popular and many people followed the plot and the characters closely. The books that came before were also popular but it was the show that really boosted the popularity of those names.

Popularity of female names | Game of Thrones
:---:|:---:
![Arya, Khaleesi, Daenerys](https://user-images.githubusercontent.com/13749006/69771412-b9ca6780-115a-11ea-977b-957ee2bf91f9.png) | ![GOT](https://user-images.githubusercontent.com/13749006/69771456-d49cdc00-115a-11ea-8a6c-bdc5958f307f.png)

### Harry Potter
In this case I just want to focus on the name 'Hermione'. It's not totally new, as shown in the left graph, but its popularity grew a lot thanks to the movies, much more than the books.

Popularity of 'Hermione' 1880-2018 | Popularity of 'Hermione' 1980-2018| Harry Potter and the Sorcerer's Stone
:---:|:---:|:---:
![Hermione 1880-2018](https://user-images.githubusercontent.com/13749006/69771795-019dbe80-115c-11ea-9fdb-5657cfdcb8b5.png) | ![Hermione 1980-2018](https://user-images.githubusercontent.com/13749006/69771803-095d6300-115c-11ea-984f-1a6847d32990.png) | ![HP](https://user-images.githubusercontent.com/13749006/69771889-59d4c080-115c-11ea-9e64-8007db349b89.png)

## Names and geography

(to be finished...)
