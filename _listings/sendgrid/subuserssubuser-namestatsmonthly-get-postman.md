{
  "info": {
    "name": "SendGrid Get Subusers Subuser Name Stats Monthly",
    "_postman_id": "17990a67-4d03-4ba1-b800-413652e8c82f",
    "description": "**This endpoint allows you to retrive the monthly email statistics for a specific subuser.**\n\nWhile you can always view the statistics for all email activity on your account, subuser statistics enable you to view specific segments of your stats for your subusers. Emails sent, bounces, and spam reports are always tracked for subusers. Unsubscribes, clicks, and opens are tracked if you have enabled the required settings.\n\nWhen using the `sort_by_metric` to sort your stats by a specific metric, you can not sort by the following metrics:\n`bounce_drops`, `deferred`, `invalid_emails`, `processed`, `spam_report_drops`, `spam_reports`, or `unsubscribe_drops`.\n\nFor more information, see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/subuser.html).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "email",
      "item": [
        {
          "id": "3965503e-36d3-455c-abba-745981b953cd",
          "name": "subusers.subuser_name.stats.monthly.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.sendgrid.com",
              "path": [
                "v3",
                "subusers/:subuser_name/stats/monthly"
              ],
              "query": [
                {
                  "key": "date",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "offset",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort_by_direction",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "sort_by_metric",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subuser_name",
                  "value": "subuser_name",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "**This endpoint allows you to retrive the monthly email statistics for a specific subuser"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d86224f-0ae5-47ec-8f3e-a23e782763ad"
            }
          ]
        }
      ]
    }
  ]
}