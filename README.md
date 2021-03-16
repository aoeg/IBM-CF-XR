###每周三 19点自动安装xray


Use GitHub Actions to automatically deploy the latest version of V2Ray to IBM Cloud Foundry

[Read the details in my blog (in Chinese) | 中文教程](https://p3terx.com/archives/how-to-use-ibm-cloud-gracefully-for-free.html)

## Usage

- Click the [Use this template](https://github.com/P3TERX/IBM-CF-V2/generate) button to create a new repository.
- Click the `Settings` tab on your own repository, and then click the `Secrets` button to add the following encrypted environment variables:

  | Environment Variables | Description |
  | --------------------- | ----------- |
  | `IBM_CF_USERNAME`       | IBM Cloud user name (email address) |
  | `IBM_CF_PASSWORD` | IBM Cloud password |
  | `IBM_CF_ORG_NAME`(optional) | Organization name, the default is the email address. Can be found on [this page](https://cloud.ibm.com/account/cloud-foundry). |
  | `IBM_CF_SPACE_NAME`(optional) | Space name, default is `dev`. Can be found on [this page](https://cloud.ibm.com/account/cloud-foundry). |
  | `IBM_CF_APP_NAME` | App name, fill in according to your preference. |
  | `XR_UUID` | Generate using UUID generator |
  | `XR_WS_PATH_VMESS` </br> `XR_WS_PATH_VLESS` | Select one of the VMess and VLESS protocols, and fill in a combination of numbers and English letters. |

- Click the `Run workflow` button on the Actions page.
- Wait for the deployment to complete.
- Click the relevant application on the [Cloud Foundry Public](https://cloud.ibm.com/cloudfoundry/public) page to view the access address.

> **TIPS:** You can customize the API address and App memory size through the workflow file.

## Acknowledgments

- [Project V](https://github.com/v2ray/v2ray-core.git)
- [Project X](https://github.com/XTLS/Xray-core.git)
- [IBM Cloud](https://cloud.ibm.com/)
- [GitHub Actions](https://github.com/features/actions)

## Licence

[MIT](https://github.com/P3TERX/IBM-CF-V2/blob/main/LICENSE) © P3TERX

## 重要信息

fork或clone本项目请低调使用，执意在任何网站上宣传并且不同意低调使用的请立刻关闭本页面离开！！！

严禁任何网友在任何网站上宣传，否则产生的一切后果自行承担！！！

感谢P3TERX提供原项目

- [IBM-CF-V2](https://github.com/P3TERX/IBM-CF-V2.git)

## Important information

Fork or clone this project, please use it in a low-key manner. If you insist on advertising on any website and do not agree with the low-key use, please close this page and leave immediately! ! !

It is strictly forbidden for any netizens to advertise on any website, otherwise all the consequences will be borne by themselves! ! !

Thank P3TERX for providing the original project

- [IBM-CF-V2](https://github.com/P3TERX/IBM-CF-V2.git)

