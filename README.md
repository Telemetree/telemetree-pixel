# TON Solutions Telemetree Pixel

## How to use
```html
<script src="/telemetree-pixel.js"></script>
<script>
    const telemetreeBuilder = telemetree({
        projectId: "YOUR_PROJECT_ID",
        apiKey: "YOUR_API_KEY",
        appName: "YOUR_APPLICATION_NAME"
    });
</script>
```

```html
<script>
    telemetreeBuilder.track('transfer', {
        amount: 1000,
        method: 'TON',
    });
</script>
```

## User data and Processing
This library is designed to automatically retrieve user data from Telegram, enhancing your events with valuable insights. 

Adhering to Telegram's high standards of security, we employ RSA encryption for the transmission of data across networks, ensuring both the integrity and safety of your analytics processes
