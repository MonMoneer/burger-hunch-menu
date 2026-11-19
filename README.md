# Burger Hunch × MOLT table menu (15 Nov 2026)

## Live

- Main: https://burgerhunchxmolt.ae/menu/ (tablet mode: add `#tablet`)
- Backup: https://monmoneer.github.io/burger-hunch-menu/

Pushes to `main` reach burgerhunchxmolt.ae automatically: a cron job on the tasjeel cPanel account pulls this repo every 5 minutes and, when there is a new commit, deploys `index.html` and `assets/` to `public_html/menu/` via `.cpanel.yml`.


Browsing-only menu for guests at the table, on a tablet or by QR. The waiter takes the order. It has no cart, no order buttons and no "Explore menu" button.

- Open `index.html` from a web host. Keep the `assets` folder next to it.
- Four categories: Burgers, Sandwiches, Appetizers (with sauces) and Drinks. Items and prices match Foodbit (app1.foodbit.io/en/burgerhunchxmolt) as checked on 15 Nov 2026.
- English and Arabic (RTL) are both included. The menu opens in Arabic on Arabic-language devices and remembers the guest's choice.
- One unified menu: no Burger Hunch or MOLT labels on dishes or sauces.
- Burgers show their add-ons (caramelised onion, jalapeño, extra cheese) at AED 3 each. French fries can be plain or seasoned.
- Tapping a dish flies its photo into a detail sheet with the description and price.
- Motion:
  - The menu opens with a short logo curtain. Tap it to skip.
  - The headline rises letter by letter, with smoke, embers and parallax.
  - Each section opens with a large title, a one-line intro and grill marks that sear in.
  - An orange tape between sections names the next section and speeds up as you scroll.
  - A progress line under the category bar shows how far down the menu the guest is.
  - All of this motion is turned off on devices set to reduce motion.
- Restaurant tablets: open the address with `#tablet` at the end. After 2 minutes without a touch, the menu closes any open dish and returns to the top for the next guest.

## Photos
- MOLT sandwiches use the 3 Nov stamp-free revision (`outputs/black-menu-20261028/revision-20261103`).
- Burger Hunch items use the Burger Hunch 23-photo set.
- Higgsfield (GPT Image 2.6) generated photos in the same slate style: Flat Tasty Burger Chicken (edited from the beef photo), Water, Sparkling Water, the soft-drink bottle line-up and the three add-on icons. The originals are in `higgsfield/`. Replace them with real photos when available.
- The hero uses a background-removed cut-out of the stamp-free Sao Paulo next to the Smokey Burger halves. The sauce cups are background-removed cut-outs of the menu photos.
