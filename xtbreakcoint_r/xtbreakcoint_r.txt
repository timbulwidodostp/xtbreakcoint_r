# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Panel cointegration test with structural breaks and cross-section dependence Use xtbreakcoint With (In) R Software
install.packages("xtbreakcoint")
library("xtbreakcoint")
# Estimation Panel cointegration test with structural breaks and cross-section dependence Use xtbreakcoint With (In) R Software
xtbreakcoint_r = read.csv("https://raw.githubusercontent.com/timbulwidodostp/xtbreakcoint_r/main/xtbreakcoint_r/xtbreakcoint_r.csv",sep = ";")
xtbreakcoint <- xtbreakcoint(xtbreakcoint ~ xtbreakcoint_, data = xtbreakcoint_r, id = "id", time = "t")
xtbreakcoint
# Panel cointegration test with structural breaks and cross-section dependence Use xtbreakcoint With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished