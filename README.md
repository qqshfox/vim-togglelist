togglelist.vim

A simple plugin for vim that allows you to bind a key to toggle the `Location
List` and the `Quickfix List`.  This plugin is currently in early development
and there aren't many things besides a few options I imagine adding.  Feel free
to submit patches.

After opening or closing either list, the previous window is restored so you
can still use `<C-w>p`.

## Mappings

    nmap <script> <silent> <leader>l :call ToggleLocationList()<CR>
    nmap <script> <silent> <leader>q :call ToggleQuickfixList()<CR>