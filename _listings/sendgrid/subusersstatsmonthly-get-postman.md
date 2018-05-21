{
  "info": {
    "name": "SendGrid Get Subusers Stats Monthly",
    "_postman_id": "e608a3d5-2a44-462a-a0c0-837216b0245c",
    "description": "**This endpoint allows you to retrieve the monthly email statistics for all subusers over the given date range.**\n\nWhile you can always view the statistics for all email activity on your account, subuser statistics enable you to view specific segments of your stats for your subusers. Emails sent, bounces, and spam reports are always tracked for subusers. Unsubscribes, clicks, and opens are tracked if you have enabled the required settings.\n\nWhen using the `sort_by_metric` to sort your stats by a specific metric, you can not sort by the following metrics:\n`bounce_drops`, `deferred`, `invalid_emails`, `processed`, `spam_report_drops`, `spam_reports`, or `unsubscribe_drops`.\n\nFor more information, see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/subuser.html).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "email",
      "item": [
        {
          "id": "5ae860a8-9852-4936-93ef-4c82fbf19a53",
          "name": "subusers.stats.monthly.get",
          "request": {
            "url": "http://api.sendgrid.com/v3/subusers/stats/monthly?date=%7B%7D&limit=%7B%7D&offset=%7B%7D&sort_by_direction=%7B%7D&sort_by_metric=%7B%7D&subuser=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "**This endpoint allows you to retrieve the monthly email statistics for all subusers over the given date range"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ef903c7-1df3-441d-bd10-384d347a3dc8"
            }
          ]
        }
      ]
    }
  ]
}