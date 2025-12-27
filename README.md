# Omni-Med

> A medical-grade autonomous robotic platform combining custom swerve-drive hardware with deep reinforcement learning for precision surgical assistance.

**The Sentient Surgical Assistant: Unifying an Agile Body with an Intelligent Mind**

A cutting-edge robotics platform showcasing medical-grade mobility with advanced autonomous navigation capabilities. This project combines custom hardware engineering with state-of-the-art AI to create a cohesive robotic instrument.

## 🎯 Project Overview

The Omni-Med platform is a medical-grade mobility solution engineered from the ground up to provide unprecedented agility, precision, and intelligence. Unlike traditional devices where mobility is an afterthought, Omni-Med's design philosophy is based on the deep integration of a custom-built hardware body with an advanced autonomous mind.

### Key Features

- **🦾 The Agile Body**: Custom co-axial swerve modules with zero-backlash harmonic drives
- **🧠 The Intelligent Mind**: Autonomous navigation powered by deep reinforcement learning
- **⚡ Extreme Precision**: Millimeter-perfect motion control for surgical applications
- **🛡️ Safety First**: Dedicated safety monitoring layer with emergency stop capabilities

## 🚀 Getting Started

### Prerequisites

- Node.js 20+ 
- npm, yarn, pnpm, or bun

### Installation

```bash
# Clone the repository
git clone https://github.com/sakethksg/ominimed.git
cd ominimed

# Install dependencies
npm install
```

### Development

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Build

```bash
npm run build
npm start
```

## 🛠️ Tech Stack

### Frontend
- **Framework**: Next.js 15.5 (App Router)
- **Styling**: Tailwind CSS 4
- **UI Components**: shadcn/ui
- **Animations**: Framer Motion & Motion
- **Icons**: Lucide React
- **Language**: TypeScript 5

### Hardware Platform
- Custom Co-Axial Swerve Modules
- High-torque pancake motors with harmonic drives
- Custom all-in-one PCB
- Monocoque aluminum chassis
- 360° LiDAR, Depth Camera, IMU sensor suite

### Autonomous Navigation Stack
- **Framework**: ROS 2 (Robot Operating System 2)
- **State Estimation**: Extended Kalman Filter (EKF)
- **Mapping**: SLAM + Adaptive Monte Carlo Localization (AMCL)
- **Path Planning**: Smac Planner (Hybrid-A*)
- **Control**: Recurrent Deep Reinforcement Learning (Soft Actor-Critic)
- **Training Environment**: NVIDIA Isaac Sim

## 📁 Project Structure

```
├── app/                      # Next.js app directory
│   ├── page.tsx             # Main landing page
│   ├── layout.tsx           # Root layout
│   ├── globals.css          # Global styles
│   └── components/          # Page-specific components
├── components/              # Reusable components
│   └── ui/                  # shadcn/ui components
├── lib/                     # Utility functions
├── public/                  # Static assets
└── plan.md                  # Project planning document
```

## 🎨 Features Showcase

### Hero Section
Animated hero with GSAP-powered LiDAR scan visualization and neural network effects.

### Hardware Platform
Interactive card-based layout showcasing:
- Drive System with co-axial swerve modules
- Integrated electronics nervous system
- Purpose-built unibody chassis

### Navigation Stack
Visual flowchart representation of the AI architecture:
- Perception & Localization layer
- Global Path Planner
- Deep RL Local Controller
- Safety & Monitoring System

## 🤝 Contributing

This is a hackathon prototype project. Contributions, issues, and feature requests are welcome!

## 📄 License

This project is private and proprietary.

## 👥 Team

Project by Saketh KSG

## 🔗 Links

- [Repository](https://github.com/sakethksg/ominimed)
- [Next.js Documentation](https://nextjs.org/docs)
- [shadcn/ui](https://ui.shadcn.com/)
- [Framer Motion](https://www.framer.com/motion/)

---

Built with ❤️ using Next.js and cutting-edge robotics technology
