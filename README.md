# D365SecurityTester
D365 FO security test tool

This tool helps you testing security setup without having to create alternate accounts.

Once imported, compile the model and restart the D365 UI. You will find a new Tile on the dashboard, called Admin access limiter.
The limiter will revoke the administrator role access for the duration of your session. I does not refresh the dashboard, but you can now only access the functionality which the other roles setup on your current account have access to. after a refresh (F5) the adminstrative accessis restored.
