#featureaplot改变标尺颜色
p1 <- FeaturePlot(object = sce2, features = "CD3D") 

p2 <- FeaturePlot(sce2, "CD3D", cols = c("#F0F921FF", "#7301A8FF"))

p3 <- FeaturePlot(sce2, "CD3D", cols = brewer.pal(10, name = "RdBu"))

p4 <- FeaturePlot(object = sce2, features = "CD3D") + 
  scale_colour_gradientn(colours = rev(brewer.pal(n = 10, name = "RdBu")))
