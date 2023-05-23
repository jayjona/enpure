# Deploy Golang API on netlify functions

[![Netlify Status](https://api.netlify.com/api/v1/badges/870141a3-3821-4391-825b-ccf11cde1546/deploy-status)](https://app.netlify.com/sites/resilient-manatee-888598/deploys)

Minimum working template to deploy a Go API in Netlify functions (AWS Lambda)
Try API [Live Version]

## 🏁 Getting Started

#### One-click deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/darkmelcof/go_api_netlify_template)

#### Manual deployment

Check the file, **.go_version** which is important to inform Netlify which version of Go you are using. 
Following [Netlify - Go Build documentation] may fail without above file.



[Netlify - Go Build documentation]: <https://docs.netlify.com/functions/build-with-go/>
[Live Version]: <https://resilient-manatee-888598.netlify.app/.netlify/functions/hello>