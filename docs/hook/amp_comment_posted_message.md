## Filter `amp_comment_posted_message`

```php
apply_filters( 'amp_comment_posted_message' );
```

Filters the message when comment submitted success message when

### Source

:link: [includes/class-amp-http.php:493](/includes/class-amp-http.php#L493)

<details>
<summary>Show Code</summary>

```php
$message = apply_filters( 'amp_comment_posted_message', $message, $comment );
```

</details>
