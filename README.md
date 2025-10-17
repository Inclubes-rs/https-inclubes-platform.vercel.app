inclubes/
├── app/
│   ├── layout.tsx           → Layout geral com identidade Inclubes (cores, fontes)
│   ├── page.tsx             → Página inicial institucional
│   ├── chat/                → Adaptado para “Feed Social”
│   ├── projetos/            → Tela de projetos de clubes
│   ├── painel/              → Dashboard de clubes
│   └── api/                 → Endpoints do backend (API Routes)
│
├── components/
│   ├── Navbar.tsx
│   ├── Footer.tsx
│   ├── ProjectCard.tsx
│   ├── ChatFeed.tsx (adaptado do chatbot)
│   └── ClubPanel.tsx
│
├── lib/
│   ├── supabaseClient.ts    → Conexão com banco (ou Firebase)
│   └── utils.ts
│
├── public/
│   └── logo-inclubes.svg
│
├── styles/
│   └── globals.css
│
├── .env.example
├── next.config.js
├── tailwind.config.js
└── package.json
