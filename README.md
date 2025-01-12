# ⚙️ macOS-workflows

Useful workflows for the macOS power user!

## 📥 Installation

1. Download each individual workflow or `all_workflows.zip` from [Releases](https://github.com/Richy-Z/macOS-workflows/releases)
2. Expand the compressed zip(s)
3. Double-click each `.workflow` file to install it in your macOS system.
4. The workflows will be available in the Quick Actions menu when you right-click on files in Finder.

## 🏃 Usage

1. Right-click on a file in Finder.
2. Select the desired workflow from the Quick Actions menu.
<!-- 3. Follow any on-screen prompts if applicable. -->

## Workflows

### Skip Apple Quarantine and Run

This workflow skips the quarantine check by removing the `com.apple.quarantine` extended attribute from the selected file using the `xattr` command.

If the selected file is an application bundle (`.app`) or an executable binary, it will then attempt to run it.

⚠️ Use this workflow with caution. Bypassing Gatekeeper's security checks can potentially expose your system to security risks. Only use this on files from trusted sources that you have verified as safe.

## ⚠️ Caution

These workflows are designed for advanced users who understand the potential risks involved in bypassing macOS security features. Always exercise caution when using these workflows, especially with files from unknown or untrusted sources.

I, the creator, contributors and maintainers are not liable for any damages or issues caused by using these workflows.

## ❤️ Contributing

Feel free to contribute additional workflows or improvements to existing ones by submitting pull requests.
