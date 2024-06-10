<div class="border-b border-b-slate-200 px-2 hidden md:block pt-5">
    <div class="flex justify-between pretendard max_screen mx-auto pb-4">
        <div>LOGO</div>
        <div>
            <ul class="flex gap-8">
                <li>메뉴1</li>
                <li>메뉴2</li>
                <li>메뉴3</li>
                <li>메뉴4</li>
                <li>메뉴5</li>
            </ul>
        </div>
    </div>
</div>

<div
    class="border-b border-b-slate-200 px-2 md:hidden pt-5 pretendard relative"
>
    <button
        class="absolute top-1/3 left-5 text-lg"
        on:click={() => {
            console.log("alidsjfljwelifjliwjef");
        }}
    >
        <i class="fa fa-bars" aria-hidden="true"></i>
    </button>
    <div class="pb-4 text-center">LOGO</div>
</div>

<div class="max_screen mx-auto suit-font py-4 px-2">
    <slot></slot>
</div>
