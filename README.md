# @demo/ui-components

Shared React UI component library consumed by downstream applications via the **Component Sync** GitHub App.

## Components

| Category | Component | Description |
|----------|-----------|-------------|
| UI | `Button` | Multi-variant button with loading state |
| UI | `Input` | Form input with label, error, and helper text |
| UI | `Badge` | Status badges (success, warning, error, info) |
| Layout | `Card` | Content card with title, subtitle, and footer |
| Layout | `Container` | Responsive max-width container |
| Feedback | `Modal` | Accessible modal dialog with ESC-to-close |
| Feedback | `Alert` | Dismissible notification banners |

## Usage

These components are automatically synced into consuming repos (e.g. `demo-repo-c`) by the [Component Sync App](https://github.com/GitHubDemoPlayground/GitHubApp).
Pushing to `main` triggers an automatic sync PR in downstream repos.
