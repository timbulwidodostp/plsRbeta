# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Partial Least Squares Regression (PLS) for Beta Regression Models Use plsRbeta With (In) R Software
install.packages("plsRbeta")
library("plsRbeta")
plsRbeta = read.csv("https://raw.githubusercontent.com/timbulwidodostp/plsRbeta/main/plsRbeta/plsRbeta.csv",sep = ";")
# Estimation Partial Least Squares Regression (PLS) for Beta Regression Models Use plsRbeta With (In) R Software
yplsRbeta <- plsRbeta$yield
XplsRbeta <- plsRbeta[,2:5]
plsRbeta <- plsRbeta(yplsRbeta,XplsRbeta,nt=3,modele="pls-beta")
print(plsRbeta)
plsRbeta$pp
plsRbeta$Coeffs
plsRbeta$Std.Coeffs
plsRbeta$InfCrit
plsRbeta$PredictY[1,]
# Partial Least Squares Regression (PLS) for Beta Regression Models Use plsRbeta With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished