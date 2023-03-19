# clfDemo
 * Stepwise Description.
  1. Created a bus topic trigger on Azure Portal.
  2. Since, the assignment was to just read the json data, hence skip the feeding part of json in topic queue
      of Azure resource.
  3. Create a Subscription queue, and added the json file manually, and activated the subscription service 
      to host the reading of json.
  4. In Visual Studio, created this azure bus topic trigger, where the method to read the json hosted in subscription 
      queue is read using shared connectionstring (path in local.setthings.json).
  5. Once the raw data is fetched within the input parameter 'productItem', the trigger function process the data
      through utility method 'ProcessProductPayloadJson', to create the desired resultant json object.
  6. Based on the mapping provided, only able to create a utility method for ProductPayload, unable to
      understand the data-obeject assignment for other payload objects such as TranslationalPayload, 
      Product2ConfigurationPayload, ProductFeaturePayload, ProductOptionPayload.
