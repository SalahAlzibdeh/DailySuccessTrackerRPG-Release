# DailySuccessTrackerRPG

[![Latest Release](https://img.shields.io/github/v/release/SalahAlzibdeh/DailySuccessTrackerRPG-Release)](https://github.com/SalahAlzibdeh/DailySuccessTrackerRPG-Release/releases/tag/v1.3)
DailySuccessTrackerRPG is a desktop productivity app built with C# and WinUI 3. It combines habit tracking, task planning, time blocking, time tracking, reading progress, and RPG-style progression into one app.

## Overview

The app uses a custom category system where the same categories you create for organization also act as XP tracks. Complete habits, tasks, subtasks, focus sessions, and finished books to level up those categories in real time.

## Features

- Progress tracking and XP-based leveling
- Habit tracking with recurring weekly schedules
- One-off tasks with subtasks
- Time blocking and time tracking
- Pomodoro timer
- Books tracking and archive
- Daily metrics and performance history
- Custom categories
- Local JSON storage with export/import support

## Download

Grab the latest release here:

https://github.com/SalahAlzibdeh/DailySuccessTrackerRPG/releases/latest

## Architecture

The app follows a simple MVVM structure:

- Models: `AppModels.cs`
- ViewModels: `HomeViewModel.cs`, `TasksViewModel.cs`
- Services: `Manager.cs`, `TimerService.cs`
- Views: WinUI 3 pages and dialogs built in C#

## Prerequisites

- Windows 10 or 11
- .NET 8.0 SDK or later if building from source
- Visual Studio 2022 with .NET Desktop Development and Windows App Development workloads

## Build from source

```bash
git clone https://github.com/SalahAlzibdeh/DailySuccessTrackerRPG.git
