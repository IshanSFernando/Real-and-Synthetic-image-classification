# Model naming convention

1. General model- general_<model_architecture>_<person>_v<number>.h5
2. Impainting   - impainting_<model_architecture>_<person>_v<number>.h5
3. StyleGan2    - gan2_<model_architecture>_<person>_v<number>.h5
4. StyleGan3    - gan3_<model_architecture>_<person>_v<number>.h5
5. Glide        - glide_<model_architecture>_<person>_v<number>.h5
6. Transformer  - transformer_<model_architecture>_<person>_v<number>.h5
  
  EX:- general_resnet_lakshan_v1.h5
  
 # Dataset folder hierarchy 

  <ul>
  <li>StyleGan2/training/v1/real/file_name</li>
  <li>StyleGan2/training/v1/synthetic/file_name</li>
  <li>StyleGan2/training/v1/real_randomOperated/file_name</li>
  <li>StyleGan2/training/v1/synthetic_randomOperated/file_name</li>
  </ul>
  <ul>
  <li>StyleGan2/test/v1/real/file_name</li>
  <li>StyleGan2/test/v1/synthetic/file_name</li>
  <li>StyleGan2/test/v1/real_randomOperated/file_name/li>
  <li>StyleGan2/test/v1/synthetic_randomOperated/file_name</li>
  </ul>
