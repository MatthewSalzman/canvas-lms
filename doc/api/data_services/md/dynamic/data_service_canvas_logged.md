Logged
==============

<h2 id="logged_in">logged_in</h2>

**Definition:** The event is emitted anytime an end user logs into Canvas

**Trigger:** Triggered when a user has logged in.




### Payload Example:

```json
{
  "metadata": {
    "client_ip": "93.184.216.34",
    "event_name": "logged_in",
    "event_time": "2019-11-01T19:11:01.335Z",
    "hostname": "oxana.instructure.com",
    "http_method": "POST",
    "producer": "canvas",
    "referrer": "https://oxana.instructure.com/idp/profile/SAML2/Redirect/SSO?execution=e1s2",
    "request_id": "1dd9dc6f-2fb0-4c19-a6c5-7ee1bf3ed295",
    "root_account_id": "21070000000000001",
    "root_account_lti_guid": "VicYj3cu5BIFpoZhDVU4DZumnlBrWi1grgJEzADs.oxana.instructure.com",
    "root_account_uuid": "VicYj3cu5BIFpoZhDVU4DZumnlBrWi1grgJEzADs",
    "session_id": "ef686f8ed684abf78cbfa1f6a58112b5",
    "url": "https://oxana.instructure.com/login/saml",
    "user_account_id": "21070000000000001",
    "user_agent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.103 Safari/537.36",
    "user_id": "21070000000000001",
    "user_login": "oxana@example.com",
    "user_sis_id": "456-T45"
  },
  "body": {
    "redirect_url": "https://oxana.instructure.com/"
  }
}
```




### Event Body Schema

| Field | Description |
|-|-|
| **redirect_url** | The URL the user was redirected to after logging in. Is set when the user logs in after clicking a deep link into Canvas. |



<h2 id="logged_out">logged_out</h2>

**Definition:** The event is emitted anytime an end user logs out of Canvas

**Trigger:** Triggered when a user has logged out.




### Payload Example:

```json
{
  "metadata": {
    "client_ip": "93.184.216.34",
    "event_name": "logged_out",
    "event_time": "2019-11-01T19:11:04.195Z",
    "hostname": "oxana.instructure.com",
    "http_method": "POST",
    "producer": "canvas",
    "referrer": "https://oxana.instructure.com/courses/1188569/quizzes/4266352?module_item_id=23650329",
    "request_id": "1dd9dc6f-2fb0-4c19-a6c5-7ee1bf3ed295",
    "root_account_id": "21070000000000001",
    "root_account_lti_guid": "VicYj3cu5BIFpoZhDVU4DZumnlBrWi1grgJEzADs.oxana.instructure.com",
    "root_account_uuid": "VicYj3cu5BIFpoZhDVU4DZumnlBrWi1grgJEzADs",
    "session_id": "ef686f8ed684abf78cbfa1f6a58112b5",
    "time_zone": "America/Los_Angeles",
    "url": "https://oxana.instructure.com/logout",
    "user_account_id": "21070000000000001",
    "user_agent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.103 Safari/537.36",
    "user_id": "21070000000000001",
    "user_login": "oxana@example.com",
    "user_sis_id": "456-T45"
  },
  "body": {}
}
```





