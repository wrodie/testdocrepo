# Sub Sub Sub Page 6

<a href="../../../../" class="button secondary">New button</a>

{% embed url="https://www.youtube.com/watch?v=sSWxWw7CWCM" %}

<figure><img src="../../../../.gitbook/assets/funny-farm-animals-01.jpg" alt="Alt text for cow image" width="188"><figcaption><p>Image Caption</p></figcaption></figure>

[images-and-media.md](../../../../basics/images-and-media.md "mention")

{% content-ref url="../../../../getting-started/quickstart.md" %}
[quickstart.md](../../../../getting-started/quickstart.md)
{% endcontent-ref %}

{% tabs %}
{% tab title="JavaScript" %}
```javascript
const message = "hello world";
console.log(message);
```
{% endtab %}

{% tab title="Python" %}
```python
message = "hello world"
print(message)
```
{% endtab %}

{% tab title="Ruby" %}
```ruby
message = "hello world"
puts message
```
{% endtab %}
{% endtabs %}

## Create a new user

<mark style="color:green;">`POST`</mark> `/users`

\<Description of the endpoint>

**Headers**

| Name          | Value              |
| ------------- | ------------------ |
| Content-Type  | `application/json` |
| Authorization | `Bearer <token>`   |

**Body**

| Name   | Type   | Description      |
| ------ | ------ | ---------------- |
| `name` | string | Name of the user |
| `age`  | number | Age of the user  |

**Response**

{% tabs %}
{% tab title="200" %}
```json
{
  "id": 1,
  "name": "John",
  "age": 30
}
```
{% endtab %}

{% tab title="400" %}
```json
{
  "error": "Invalid request"
}
```
{% endtab %}
{% endtabs %}

{% content-ref url="../../../../getting-started/publish-your-docs.md" %}
[publish-your-docs.md](../../../../getting-started/publish-your-docs.md)
{% endcontent-ref %}

* [ ] task list
