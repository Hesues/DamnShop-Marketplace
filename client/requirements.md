## Packages
zustand | For shopping cart state management
recharts | For admin dashboard charts
date-fns | For date formatting
lucide-react | Icons

## Notes
- Tailwind Config - extend fontFamily:
fontFamily: {
  sans: ["var(--font-sans)"],
  display: ["var(--font-display)"],
}
- Backend uses /api/auth/* for authentication (cookie-based session).
- Currency is PHP (cents in backend, display divided by 100).
- Uses existing Shadcn UI components.
