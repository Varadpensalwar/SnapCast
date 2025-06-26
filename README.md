# SnapCast

SnapCast is a modern video sharing platform built with Next.js, where users can upload, view, and manage videos.

## Live Demo

Visit the live application: [https://snapcast-lime.vercel.app/](https://snapcast-lime.vercel.app/)

## Features

- **Video Upload**: Upload videos with thumbnails, titles, and descriptions
- **Video Playback**: Watch videos with a clean, user-friendly interface
- **User Profiles**: View videos by specific users
- **Public Library**: Browse all public videos
- **Video Privacy**: Set videos as public or private
- **Responsive Design**: Works on desktop and mobile devices

## Technology Stack

- **Frontend**: React 19, Next.js 15
- **Styling**: Tailwind CSS
- **Authentication**: Better Auth
- **Database**: PostgreSQL with Drizzle ORM
- **Video Storage**: BunnyCDN (based on upload implementation)

## Getting Started

### Prerequisites

- Node.js (latest LTS version recommended)
- PostgreSQL database

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Varadpensalwar/SnapCast.git
   cd SnapCast
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Set up environment variables (create a `.env` file in the root directory)

4. Run the development server
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure

- `/app`: Next.js app router pages and layouts
- `/components`: Reusable React components
- `/lib`: Utility functions and API actions
- `/public`: Static assets

## License

This project is open source and available under the MIT License.
