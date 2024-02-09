# Farwello

### Usage
- Users can submit leave requests
- Admins & Moderators can view and edit submitted leaves
- Approved leaves trigger automatic balances updates
- Everyone can view the Organisational Calendar and see upcoming events
- Admins can add settings and edit balances


### Tech-Stack
The app was built using the following technologies:

- Next.js as the React framework
- Prisma as the ORM for migrations and database access
- PostgreSQL: database for local testing
- Next-Auth/Authjs: for authentication
- TypeScript: the programming language
- TailwindCSS: Styling
- shadcn/ui for UI components



#### Clone the repo
`https://github.com/piyushyadav0191/farewello `

Install packages
`pnpm `

#### Setup the .env file
- See the `.env.example ` file

#### Setup Prisma
`pnpm prisma generate`
`pnpm prisma migrate dev `

#### Start the app
`pnpm dev`
