
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/reports/applicationSignInDetailedSummary/'id'')
	.version('beta')
	.get();

```