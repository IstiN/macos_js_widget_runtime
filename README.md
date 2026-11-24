> **MOVED:** объединено в [apple_js_widget_runtime](https://github.com/IstiN/apple_js_widget_runtime) — JSC-ядро шарится 100% между iOS/macOS, отличия только в UIKit/AppKit маппинге. Issues #1/#2 закрыты там же.

# macos_js_widget_runtime

macOS renderer for jsr widgets: JavaScriptCore + JSON tree to AppKit/SwiftUI.

Part of the jsr family:
- Contract + conformance: [js_widget_runtime](https://github.com/IstiN/js_widget_runtime) (PROTOCOL.md is the binding test spec)
- Runtime core: [js_runtime](https://github.com/IstiN/js_runtime)
- Reference renderer: [flutter_js_widget_runtime](https://github.com/IstiN/flutter_js_widget_runtime)
- Android: [android_js_widget_runtime](https://github.com/IstiN/android_js_widget_runtime)

Engine notes: Same decision space as iOS: JSC vs embedded QuickJS.

Status: **planning** — see issues. Conformance must pass per
[js_widget_runtime/docs/conformance/PROTOCOL.md](https://github.com/IstiN/js_widget_runtime/blob/main/docs/conformance/PROTOCOL.md).
