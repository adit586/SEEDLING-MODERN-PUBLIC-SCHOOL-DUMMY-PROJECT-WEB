
@tailwind base;
@tailwind components;
@tailwind utilities;

/* Yellow and black school design system with green text */

@layer base {
  :root {
    --background: 45 100% 96%;
    --foreground: 120 100% 25%;

    --card: 45 100% 98%;
    --card-foreground: 120 100% 25%;

    --popover: 45 100% 98%;
    --popover-foreground: 120 100% 25%;

    --primary: 45 100% 50%;
    --primary-foreground: 0 0% 0%;

    --secondary: 45 100% 85%;
    --secondary-foreground: 120 100% 25%;

    --muted: 45 100% 90%;
    --muted-foreground: 120 60% 35%;

    --accent: 45 100% 88%;
    --accent-foreground: 120 100% 25%;

    --destructive: 0 84% 60%;
    --destructive-foreground: 45 100% 98%;

    --border: 45 50% 80%;
    --input: 45 50% 80%;
    --ring: 45 100% 50%;

    --radius: 1rem;

    /* Custom colors - yellow, black, and green theme */
    --pastel-blue: 45 100% 85%;
    --pastel-green: 120 100% 85%;
    --pastel-yellow: 45 100% 90%;
    --pastel-pink: 45 100% 88%;
    --pastel-purple: 45 100% 86%;
    --pastel-orange: 45 100% 82%;
  }

  .dark {
    --background: 0 0% 8%;
    --foreground: 120 100% 70%;

    --card: 0 0% 8%;
    --card-foreground: 120 100% 70%;

    --popover: 0 0% 8%;
    --popover-foreground: 120 100% 70%;

    --primary: 45 100% 50%;
    --primary-foreground: 0 0% 0%;

    --secondary: 0 0% 15%;
    --secondary-foreground: 120 100% 70%;

    --muted: 0 0% 15%;
    --muted-foreground: 120 60% 50%;

    --accent: 0 0% 15%;
    --accent-foreground: 120 100% 70%;

    --destructive: 0 63% 31%;
    --destructive-foreground: 45 100% 98%;

    --border: 0 0% 15%;
    --input: 0 0% 15%;
    --ring: 45 100% 50%;
  }
}

@layer base {
  * {
    @apply border-border;
  }

  body {
    @apply bg-background text-foreground;
    font-family: 'Inter', sans-serif;
  }
}

@layer components {
  .pastel-blue {
    background-color: hsl(var(--pastel-blue));
  }
  
  .pastel-green {
    background-color: hsl(var(--pastel-green));
  }
  
  .pastel-yellow {
    background-color: hsl(var(--pastel-yellow));
  }
  
  .pastel-pink {
    background-color: hsl(var(--pastel-pink));
  }
  
  .pastel-purple {
    background-color: hsl(var(--pastel-purple));
  }
  
  .pastel-orange {
    background-color: hsl(var(--pastel-orange));
  }

  .floating-animation {
    animation: gentle-float 6s ease-in-out infinite;
  }

  .soft-hover {
    transition: all 0.3s ease;
  }

  .soft-hover:hover {
    transform: translateY(-4px);
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
  }

  .disclaimer-banner {
    background: linear-gradient(135deg, hsl(var(--pastel-yellow)), hsl(var(--pastel-orange)));
  }
}

@keyframes gentle-float {
  0%, 100% {
    transform: translateY(0px);
  }
  50% {
    transform: translateY(-10px);
  }
}

@keyframes fade-in-up {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.animate-fade-in-up {
  animation: fade-in-up 0.8s ease-out;
}
