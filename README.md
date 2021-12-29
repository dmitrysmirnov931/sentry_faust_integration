# Faust integration for Sentry
Faust integration build for Sentry.
## Usage
```
import sentry_sdk
from sentry_faust_integration import FaustIntegration


sentry_sdk.init(
    integrations=[
        FaustIntegration()
    ]
)
```