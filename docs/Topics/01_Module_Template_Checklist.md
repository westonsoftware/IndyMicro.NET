## TOPIC 01

# Module Template Checklist

After creating a new module project you will need to review the generated code and update or remove the following features that apply to your situation:

- review \Models
- review \Models\ViewModels
- review \Data\Repositories for your models
- review \Data\SampleDbContext
  - replace the initial migration
- review \Security policies
  - add new permissions to swagger test token
- review \Messages
- review \Services\SampleMessageService
- review \Notifications hub events
  - use \wwwroot\js\SampleHub.js
- review \Areas\Sample\Controllers for api's
  - use Authorize policys
- check swagger
- review the UI for Admin Razor pages
  - review \Areas\Sample\Pages\Shared\_Layout.cshtml
  - review \Areas\Sample\Pages\Shared\Components
  - review \Areas\Sample\Pages



[< Back](index.md)





