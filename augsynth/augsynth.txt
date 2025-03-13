# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Augmented synthetic control method Use augsynth With (In) R Software
install.packages("remotes")
remotes::install_github("ebenmichael/augsynth")
library("augsynth")
augsynth = read.csv("https://raw.githubusercontent.com/timbulwidodostp/augsynth/main/augsynth/augsynth.csv",sep = ";")
# Estimation Augmented synthetic control method Use augsynth With (In) R Software
augsynth <- augsynth(lngdpcapita ~ treated, fips, year_qtr, augsynth, progfunc = "None", scm = T)
summary(augsynth)
# Augmented synthetic control method Use augsynth With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished