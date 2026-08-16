# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Calculate Krippendorff's alpha reliability coefficient Use kripp.alpha (irr) With (In) R Software
install.packages("irr")
library("irr")
# Estimation Calculate Krippendorff's alpha reliability coefficient Use kripp.alpha (irr) With (In) R Software
kripp.alpha = read.csv("https://raw.githubusercontent.com/timbulwidodostp/kripp.alpha/main/kripp.alpha/kripp.alpha.csv",sep = ";")
kripp_alpha_2_ = cbind(kripp.alpha$kripp.alpha_1, kripp.alpha$kripp.alpha_2, kripp.alpha$kripp.alpha_3, kripp.alpha$kripp.alpha_4)
kripp_alpha_3_ = cbind(kripp.alpha$kripp.alpha_1, kripp.alpha$kripp.alpha_2, kripp.alpha$kripp.alpha_3)
kripp_alpha_4_ = cbind(kripp.alpha$kripp.alpha_1, kripp.alpha$kripp.alpha_2)
kripp_alpha_1 = as.matrix(kripp.alpha)
kripp_alpha_2 = as.matrix(kripp_alpha_2_)
kripp_alpha_3 = as.matrix(kripp_alpha_3_)
kripp_alpha_4 = as.matrix(kripp_alpha_4_)
kripp.alpha_1 <- kripp.alpha(kripp_alpha_1)
kripp.alpha_2 <- kripp.alpha(kripp_alpha_2)
kripp.alpha_3 <- kripp.alpha(kripp_alpha_3)
kripp.alpha_4 <- kripp.alpha(kripp_alpha_4)
kripp.alpha_1
kripp.alpha_2
kripp.alpha_3
kripp.alpha_4
# Calculate Krippendorff's alpha reliability coefficient Use kripp.alpha (irr) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished