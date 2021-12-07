# Peform the same Task that you have done with Assignment 9 using AWS CodeBuild and CodePipeline. Whenever there is a merge to master branch the pipeline should get triggered automatically and the container should built and stored in ECR

# keynotes

_policy:_ Attach policy **AmazonElasticContainerRegistryPublicFullAccess** policy to codebuild-service-role</br>

_adding docker credentials:_

![image](https://user-images.githubusercontent.com/63493140/144968905-08026e38-e621-438b-adce-79d2da50568a.png)

# outputs

_image successfully pushed to ECR_

![image](https://user-images.githubusercontent.com/63493140/144968199-62620eda-6e6f-436c-a13d-3db2379ad4b1.png)

_pipeline stages_

![image](https://user-images.githubusercontent.com/63493140/144968618-2372ff1f-fdea-4792-a3fe-ad2ae6fab195.png)
