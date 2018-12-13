# @acpaas/monitor

> This package contains the monitor functionality ocapi services 

## Install
```bash
npm install @acpaas/monitor
```  

## Usage
```javascript
app.use(require("@acpaas/monitor")({
	"api": {
		"version": "0.2.5",
		"name": "deliverable-management",
	},
	"dependencies": [
		presets.api_manager,
		presets.workplace,
	],
}));
```

This will expose a /status/monitor & /status/ping route
