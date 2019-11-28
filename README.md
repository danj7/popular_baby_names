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

## Names and the movies

(To be finished...)
