# A70-
boxplot (  
 real_time_seconds ~ verified, 
  data,
  main = "Difference in the mean of real life time speed run took between \n verified and non-verified members",
  xlab = "Verified",
  ylab = "Real life Time the Speedrun took in seconds",
  ylim = c(0, 1200),
  pch = 1,
  cex = 0.7,
  col = c("lightgreen", "steelblue")
)

legend(
  x = "topright",
  legend = c("Non-Verified", "Verified"),
  lwd = 2,
  lty = c(0, 0),
