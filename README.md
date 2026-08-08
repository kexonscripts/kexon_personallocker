## kexon_personallocker

Character-based personal storage system. Each player gets their own persistent locker tied to their character identifier, accessible at physical locker locations around the map.

**Features:**
- Persistent, character-based personal storage via ox_inventory stashes
- Full server-side validation — no client-trusting, no duplication exploits
- Upgradeable slots (50 base, 100 max) and weight (100,000 base, 250,000 max)
- Bulk upgrades — purchase 1 to 10 upgrades at once via ox_lib input dialog
- Money-based economy — upgrades deduct cash from inventory automatically
- Configurable locker zones with custom coordinates, box size, and rotation
- Full Discord webhook audit logging — locker opens, upgrades, item deposits, item withdrawals
- Real-time swapItems hook logs every item movement in and out of lockers
- Auto-creates database table on first startup — no manual SQL import required
- Customizable webhook name and avatar image

**Dependencies:** ESX, ox_lib, ox_inventory, oxmysql
