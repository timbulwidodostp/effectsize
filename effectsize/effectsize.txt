# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Cohen's d and Hedges g effect size Use cohens_d and hedges_g (effectsize) With (In) R Software
install.packages("jtools")
library("jtools")
# Estimation Cohen's d and Hedges g effect size Use cohens_d and hedges_g (effectsize) With (In) R Software
effectsize = read.csv("https://raw.githubusercontent.com/timbulwidodostp/effectsize/main/effectsize/effectsize.csv",sep = ";")
cohens_d_1 <- cohens_d(effectsize_1 ~ effectsize, data = effectsize)

hedges_g_1 <- hedges_g(effectsize_1 ~ effectsize, data = effectsize)
cohens_d_2 <- cohens_d(effectsize_2 ~ effectsize, data = effectsize)

hedges_g_2 <- hedges_g(effectsize_2 ~ effectsize, data = effectsize)
cohens_d_3 <- cohens_d(effectsize_3 ~ effectsize, data = effectsize)

hedges_g_3 <- hedges_g(effectsize_3 ~ effectsize, data = effectsize)
cohens_d_1

hedges_g_1

cohens_d_2

hedges_g_2

cohens_d_3

hedges_g_3

# Cohen's d and Hedges g effect size Use cohens_d and hedges_g (effectsize) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished