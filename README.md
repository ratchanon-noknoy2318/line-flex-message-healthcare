# LINE Patient Communication System 📱🏥

A professional **LINE Official Account (OA)** automation system designed to streamline patient-provider communication. By leveraging the LINE Messaging API and custom Webhooks, this system provides a structured, app-like experience directly within the LINE interface.

## 🚀 Impact & Innovation

- **Enhanced UX**: Designed and implemented an **8-grid Rich Menu**, providing patients with instant access to critical services like appointment booking, results, and FAQs.
- **Structured Messaging**: Created **11 custom Flex Messages (JSON)** to deliver medical information, reminders, and confirmations in a clear, readable, and interactive format.
- **Workflow Automation**: Integrated Webhook logic to handle patient inquiries automatically, reducing the manual workload for hospital staff.

## 📋 Features

- **Automated Triage**: Initial patient interaction handled via automated webhook logic.
- **Dynamic Flex Messages**: Rich, interactive UI components that allow patients to click buttons, view carousels, and receive formatted medical alerts.
- **Persistent Rich Menu**: An 8-button navigation grid that serves as the "Home Screen" of the hospital's LINE account.
- **Seamless Scalability**: Built to handle high-volume messaging during peak clinic hours.

## 🛠️ Tech Stack

- **Platform**: LINE Messaging API
- **Backend**: Node.js (Webhook Server)
- **UI/UX**: JSON-based Flex Messages & Rich Menu Design
- **Integration**: Webhook-driven automation

## 🏗️ Architecture

The system operates on a request-response cycle optimized for mobile performance:
`Patient (LINE App)` ↔️ `LINE Platform` ↔️ `Node.js Webhook Server` ↔️ `Clinical Logic/Database`

## 📂 Repository Structure

- `/flex-templates`: JSON schemas for the 11 clinical Flex Messages.
- `/rich-menu`: Configuration and assets for the 8-grid navigation menu.
- `/src`: Webhook handling logic and message routing.

## 🚀 Getting Started

1. **LINE Developers Console**: Create a Provider and a Messaging API channel.
2. **Webhook Setup**: Deploy the Node.js server and set the Webhook URL in the LINE Console.
3. **Configure Rich Menu**: Use the scripts in `/rich-menu` to upload the 8-grid layout to your LINE OA.

## 🛡️ Security & Privacy
This system is designed to facilitate communication while maintaining data privacy. No PII (Personally Identifiable Information) is logged in the webhook transit unless explicitly required by the clinical database.

## 📄 License
MIT License
