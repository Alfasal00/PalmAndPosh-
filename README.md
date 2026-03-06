# PalmAndPosh
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Palm & Posh | Catalog</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&family=Montserrat:wght@300;400;500;600&display=swap');
        
        body {
            font-family: 'Montserrat', sans-serif;
            background-color: #FCFbf9; /* Soft cream */
            color: #4a4a4a;
        }
        
        .font-serif { font-family: 'Playfair Display', serif; }
        .text-palm-green { color: #6b7a57; }
        .bg-palm-green { background-color: #6b7a57; }
        .text-posh-pink { color: #e8a3b1; }
        .text-deep-red { color: #8b0000; } 

        .glass-card {
            background: rgba(255, 255, 255, 0.9);
            border: 1px solid rgba(232, 163, 177, 0.2);
            box-shadow: 0 4px 20px 0 rgba(107, 122, 87, 0.05);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .glass-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px 0 rgba(107, 122, 87, 0.1);
        }
    </style>
</head>
<body class="bg-[url('https://www.transparenttextures.com/patterns/cream-paper.png')] pb-24">

    <header class="bg-white/80 backdrop-blur-md sticky top-0 z-50 border-b border-gray-100 shadow-sm">
        <div class="max-w-md mx-auto px-4 py-4 flex items-center justify-between">
            <div class="flex items-center gap-2">
                <i class="fas fa-leaf text-palm-green text-xl"></i>
                <h1 class="font-serif text-2xl font-bold text-palm-green tracking-tight">Palm & Posh</h1>
            </div>
            <a href="https://www.instagram.com/palm_andposh" target="_blank" class="text-posh-pink text-2xl">
                <i class="fab fa-instagram"></i>
            </a>
        </div>
    </header>

    <main class="max-w-md mx-auto px-4 py-6 space-y-8">
        
        <div class="text-center space-y-3 bg-palm-green text-white p-6 rounded-3xl shadow-lg relative overflow-hidden">
            <h2 class="font-serif text-3xl font-bold