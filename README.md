# evaluacionM2
PE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://rsms.me/inter/inter.css">
    <link rel="encuesta" href="encuesta.html"

    <style>
    div{
color: darkcyan;
border: 6px;
background-repeat: repeat;
    }
    </style>
</head>
<body>
    <header class="p-6 dark:bg-gray-100 dark:text-gray-900">
        <form novalidate="" action="" class="container flex flex-col mx-auto space-y-12">
            <fieldset class="grid grid-cols-4 gap-6 p-6 rounded-md shadow-sm dark:bg-gray-50">
                <div class="space-y-2 col-span-full lg:col-span-1">
                    <p class="font-medium">Imformacion personal </p>
                    <p class="text-xs">UN formulario personal </p>
                </div>
                <div class="grid grid-cols-6 gap-4 col-span-full lg:col-span-3">
                    <div class="col-span-full sm:col-span-3">
                        <label for="firstname" class="text-sm">Primer nombre </label>
                        <input id="firstname" type="text" placeholder="First name" class="w-full rounded-md focus:ring focus:ring-opacity-75 dark:text-gray-50 focus:dark:ring-violet-600 dark:border-gray-300">
                    </div>
                    <div class="col-span-full sm:col-span-3">
                        <label for="lastname" class="text-sm">Segundo Nombre  </label>
                        <input id="lastname" type="text" placeholder="" class="w-full rounded-md focus:ring focus:ring-opacity-75 dark:text-gray-50 focus:dark:ring-violet-600 dark:border-gray-300">
                    </div>
                    <div class="col-span-full sm:col-span-3">
                        <label for="email" class="text-sm">Email</label>
                        <input id="email" type="email" placeholder="Email" class="w-full rounded-md focus:ring focus:ring-opacity-75 dark:text-gray-50 focus:dark:ring-violet-600 dark:border-gray-300">
                    </div>
                    <div class="col-span-full">
                        <label for="address" class="text-sm">Telefono</label>
                        <input id="address" type="text" placeholder="" class="w-full rounded-md focus:ring focus:ring-opacity-75 dark:text-gray-50 focus:dark:ring-violet-600 dark:border-gray-300">
                    </div>
                    <div class="col-span-full sm:col-span-2">
                        <label for="city" class="text-sm">ciudad</label>
                        <input id="city" type="text" placeholder="" class="w-full rounded-md focus:ring focus:ring-opacity-75 dark:text-gray-50 focus:dark:ring-violet-600 dark:border-gray-300">
                    </div>
                    <div class="col-span-full sm:col-span-2">
                        <label for="state" class="text-sm">State / Municipio</label>
                        <input id="state" type="text" placeholder="" class="w-full rounded-md focus:ring focus:ring-opacity-75 dark:text-gray-50 focus:dark:ring-violet-600 dark:border-gray-300">
                    </div>
                    
                </div>
            </fieldset>
            <fieldset class="grid grid-cols-4 gap-6 p-6 rounded-md shadow-sm dark:bg-gray-50">
                <div class="space-y-2 col-span-full lg:col-span-1">
                    <p class="font-medium">Profecional/p>
                    <p class="text-xs">Adipisci fuga autem eum!</p>
                </div>
                <div class="grid grid-cols-6 gap-4 col-span-full lg:col-span-3">
                    <div class="col-span-full sm:col-span-3">
                        <label for="username" class="text-sm">Usuario</label>
                        <input id="username" type="text" placeholder="Username" class="w-full rounded-md focus:ring focus:ring-opacity-75 dark:text-gray-50 focus:dark:ring-violet-600 dark:border-gray-300">
                    </div>
                    <div class="col-span-full sm:col-span-3">
                        <label for="website" class="text-sm">Web</label>
                        <input id="website" type="text" placeholder="https://" class="w-full rounded-md focus:ring focus:ring-opacity-75 dark:text-gray-50 focus:dark:ring-violet-600 dark:border-gray-300">
                    </div>
                    <div class="col-span-full">
                        <label for="bio" class="text-sm">Bio</label>
                        <textarea id="bio" placeholder="" class="w-full rounded-md focus:ring focus:ring-opacity-75 dark:text-gray-50 focus:dark:ring-violet-600 dark:border-gray-300"></textarea>
                    </div>
                    <div class="col-span-full">
                        <label for="bio" class="text-sm">Photo</label>
                        <div class="flex items-center space-x-2">
                            <img src="https://source.unsplash.com/30x30/?random" alt="" class="w-10 h-10 dark:bg-gray-500 rounded-full dark:bg-gray-300">
                            <button type="button" class="px-4 py-2 border rounded-md dark:border-gray-800">Change</button>
                        </div>
                    </div>
                </div>
            </fieldset>
        </form>
    </header>
</body>
</html>
