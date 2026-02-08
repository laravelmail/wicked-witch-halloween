# Wicked Witch Halloween

Professional email template for promoting a Wicked Witch themed Halloween event in the Entertainment and Retail industries.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Entertainment, Retail
- **Message Type:** Marketing
- **Tags:** promotion, halloween, witch, event

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/wicked-witch-halloween.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/wicked-witch-halloween/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.wicked-witch-halloween',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
