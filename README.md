# normal-variability

########################
#    Load Packages     #
########################

library(ggplot2)
library(reshape)
library(reshape2)
library(GGally)
library(pheatmap)
library(RColorBrewer)
library(knitr)
library(xlsx)

#################################
#    Set Initial Parameters     #
#################################

theme1 = theme_bw() + theme(text = element_text(face = "bold", size = 20))
theme0 = theme_bw() + theme(text = element_text(face = "bold", size = 10))
noleg = theme(legend.position = "none")
topleg = theme(legend.position = "top")
toprightleg = theme(legend.position = "topright")
angle45 = theme(axis.text.x = element_text(angle = 45, hjust = 1))
noxtitle = theme(axis.title = element_blank())
noxlabel = theme(axis.text.x = element_blank())
nolegtitle = theme(legend.title = element_blank())

