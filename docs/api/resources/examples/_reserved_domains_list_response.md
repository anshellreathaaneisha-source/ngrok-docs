<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-09-08T10:07:40Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.4uhtazjtprubczbqi.local-ngrok-cname.com",
      "created_at": "2025-09-08T10:07:39Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32PdILLElvZr140hqiQeFCJFZ1l",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32PdILLElvZr140hqiQeFCJFZ1l"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_32PdIHFxy8BCQ94u4w7GTE4vSGg",
        "uri": "https://api.ngrok.com/tls_certificates/cert_32PdIHFxy8BCQ94u4w7GTE4vSGg"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.4uhtazjtprubczbqi.local-ngrok-cname.com",
      "created_at": "2025-09-08T10:07:39Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32PdIEsCyHG6iRdBrq2iuXbpUhR",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32PdIEsCyHG6iRdBrq2iuXbpUhR"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-09-08T10:07:09Z",
      "description": "Your dev domain",
      "domain": "squallier-tari-fiduciarily.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_32PdEU8yH0Vrho0hlAeKhgu1yuw",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_32PdEU8yH0Vrho0hlAeKhgu1yuw"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
