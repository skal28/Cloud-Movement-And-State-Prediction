# Cloud-Movement-And-State-Prediction
 •Project is inspired from given research paper
    Automatically Adjusting Cloud Movement Prediction Model from Satellite .tiff Images
    • Language used–python3
    • Software used–  Google Colab
    • Algorithms Used- Image Segmentation K-Means, Connected component labeling, Adjusted Mean Prediction Model,
      Convolutional   L.S.T.M.
    • DataSet is collected from Smart India Hackathon 2020 I.S.R.O. problem statement and are of INSAT3D satellite
    • Formation cloud cluster by image segmentation and the higher cluster center values signifies dense cloud,
      finding the center of mass of all the points in cloud cluster and applying the adjusted mean prediction
      model to predict the value of the cluster after observing the data-set, after prediction the image of the
      cloud cluster is predicted using ConvLSTM. 

    •Actual cloud image 
    
    •Actual cloud cluster image 
    
    •Actual cloud cluster centroid for given dataset 
    
    •Actual cloud cluster center of mass of dataset
       
    •Cloud cluster centroid for given dataset by prediction model
    
    •Cloud cluster center of mass of dataset by prediction model
       
     x-coordinate
    
     y-coordinate
    
     •Cloud cluster centroid for given dataset by adjusted mean prediction model
    
    •Cloud cluster center of mass of dataset by adjusted mean prediction model
       
     x-coordinate
    
     y-coordinate
    
    •Comparision of actual and 2 predicted model of cluster centroid pixel values
    
    •Comparision of actual and 2 predicted model of cluster center of mass values
    
    • Mean Square value using basic prediction model = (0.93153902775733735 0.212739659131664)
    • Mean Square value using basic adjusted mean prediction model = (0.924637760625794 0.139216633193592)
