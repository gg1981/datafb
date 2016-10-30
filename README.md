# datafb
This data were manually taken from facebook official fan page of 4 series
#####Scandal
#####Grey's anatomy
#####How to get away with murder
#####The catch

Every row is a post in one of the pages.
The variables are named in italian but their are easy to undersand. Here the description from the first until the last column
*1 TITOLO : Title - the name of the serie
*2 EPISODIO : Episode - the number of the episod and season
*3 DATA : Date - the date of the post
*4 TIPO : Type - the type of content of the post
*5 LIKE : the number of likes for a certain post
*6 COMMENTI : Comments - the number of the comments for that post
*7 CONDIVISIONI : Reposts - the numbers of repost for that post
*8 VISUALIZZAZIONI : Visualizations - only for video, is the number of visualization for a video
*9 ASHTAG : the ashtag of a post

The following variables are created from the variable DATA (date) and they are useful for the plots 
*10 Mese : Month mm 
*11 Anno : Year yyyy
*12 MeseAnno : MonthYear mm/yyyy
*13 AnnoMese : YearMonth yyyy/mm
*14 Week : first day of the week (starting Sunday)
