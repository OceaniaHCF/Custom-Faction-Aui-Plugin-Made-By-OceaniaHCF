balances: {}
##################################################################
#Currently Only Supports Vault and Aquacore                      #
##################################################################
PERMISSION-PLUGIN: "VAULT" # VAULT or AQUACORE
combat-place: false
ktk-points: 5
conquest-points: 100
koth-points: 25
death-signs: true
diamond-ore-notifications: true
death-lightning: true
modified-launch-event: true
kit-map: true
kit-map-stats-in-spawn-only: false
prevent-ally-damage: true
core-enderpearls: true
exp-multiplier:
  global: 2.0
  fishing: 2.0
  smelting: 2.0
  looting-per-level: 1.5
  luck-per-level: 1.5
  fortune-per-level: 1.5
roads:
  allow-claims-besides: true
  nametags:
    enabled: true
combatlog:
  enabled: true
  despawn-delay-ticks: 600
conquest:
  point-loss-per-death: 20
  victory-points: 300
  allow-negative-points: false
warzone:
  radius: 600
factions:
  disallowed-faction-names:
  - EOTW
  min-name-characters: 3
  max-name-characters: 16
  max-members: 25
  max-allies: 1
subclaims:
  min-name-characters: 1
  max-name-characters: 20
relation-colours:
  wilderness: DARK_GREEN
  warzone: DARK_RED
  teammate: GREEN
  ally: BLUE
  enemy: RED
  road: GOLD
LFF-COOLDOWN: 3600 #In Seconds
LFA-COOLDOWN: 3600 #In Seconds
deaths-till-raidable:
  maximum: 6
  millis-between-updates: 45000
  increment-between-updates: 0.1
deathban:
  base-duration-minutes: 120
  respawn-screen-seconds-before-kick: 15
enchantment-limits:
  PROTECTION_ENVIRONMENTAL: 1
  PROTECTION_FIRE: 0
  SILK_TOUCH: 1
  DURABILITY: 3
  PROTECTION_EXPLOSIONS: 0
  LOOT_BONUS_BLOCKS: 3
  PROTECTION_PROJECTILE: 0
  OXYGEN: 0
  WATER_WORKER: 0
  THORNS: 0
  DAMAGE_ALL: 1
  ARROW_KNOCKBACK: 0
  KNOCKBACK: 0
  FIRE_ASPECT: 0
  LOOT_BONUS_MOBS: 3
  LUCK: 3
  LURE: 3
ENDEXIT:
  x: 0
  y: 71
  z: 0
ENDSPAWN:
  x: 0
  y: 100
  z: 0
eotw:
  chat-symbol-prefix: ""
  chat-symbol-suffix: ""
  last-map-cappers: []
KOTH-COMMAND: "cr givekey %winner% koth 3"
CONQUEST-COMMAND: "cr givekey %winner% conquest 1"
FROZEN-LOGOUT-AUTOBAN: TRUE
FROZEN-LOGOUT-COMMAND: "ban %player% Logging Out Whilst Frozen."
DEFAULT-APPLE-COOLDOWN: 15 #In Seconds
DEFAULT-GOPPLE-COOLDOWN: 3600 #In Seconds
SCOREBOARD-FOOTER: FALSE
HCF-DTR-REGEN-TIME: 300 #In Seconds
STARTING-BALANCE: 2500
ROGUE-SPEED-COOLDOWN: 30
ARCHER-JUMPBOOST-COOLDOWN: 30
RECORDING-COOLDOWN: 300
factions: {}
users: {}
ability-disabled: "&cThis ability is not enabled this map."
invalid-amount: "&cYou have specified an invalid amount."
damager-swapped-location: "&eYou have swapped locations with %player%"
damaged-swapped-locations: "&eYou have been forced to switch locations with %player%"
snowport-given-single: "&eYou have given %player% a snowport."
snowport-given-multiple: "&eYou have given %player% %amount% snowport's"
belchbomb-given-single: "&eYou have given %player% a belch bomb."
belchbomb-given-multiple: "&eYou have given %player% %amount% belch bomb's"
grappling-hook-given: "&eYou have given %player% a grappling hook."
snowport:
  enabled: true
  name: "&f&lSwitcher"
  radius:
    enabled: true
    radius: 10
  lore:
    - '&cWhen you hit a player you will swap positions with them.'
  cooldown: 15
  remaining: "&eYou are still on cooldown for %remaining%"
  refund: true
grapplinghook:
  enabled: true
  name: "&6&lGrappling Hook"
  lore:
    - '&cThrow the hook and retract it to travel to the hooks location!'
  cooldown: 15
  remaining: "&eYou are still on cooldown for %remaining%":
  enabled: true
  name: "&a&lFlashBang"
  lore:
    - '&cRight-Click this item to give your enemys blindness and slowness.'
  cooldown: 30
  radius: 15
  duration: 5
  amplifier: 2
  selfeffect:
    duration: 5
    amplifier: 2
  remaining: "&eYou are still on cooldown for %remaining%"
 lives: {}
ENDEXIT:
  X: 0
  Y: 75
  Z: 0
ENDSPAWN:
  X: 0
  Y: 100
  Z: 0
# %player% returns the players name
# %rank% returns the players rank name
reclaims:
SERVER-NAME: "&4&lOceania:"
SERVER-WEBSITE: "&7oceania-network-store.tebex.io"
END-PORTAL: "&4&lEnd Portals:"
END-PORTAL-COORDNATES: "&71000,1000"
END-PORTAL-QUADRENTS: "&7In each quadrant"
MAP-KIT: "&4Kit:"
MAP-KIT-ENCHANTS: "&7Prot 1, Sharp 1"
WORLD-BORDER: "&4Border:"
WORLD-BORDER-SIZE: "&73000"
PLAYER-INFO: "&4Player Info:"
PLAYER-INFO-KILLS: "&7Kills: %kills%"
PLAYER-INFO-DEATHS: "&7Deaths: %deaths%"
disable_obsidian_generators: true
server_time_zone: "GMT+1"
warzone_radius: 850
disallowed_faction_names:
    - "kohieotw"
    - "kohisotw"
    - "hcteams"
    - "hcteamsseotw"
    - "hcteamssotw"
    - "para"
    - "parahcf"
    - "parasotw"
    - "paraeotw"
enchantment_limits:
    PROTECTION_ENVIRONMENTAL: 1
    DAMAGE_ALL: 1
    ARROW_KNOCKBACK: 0
    KNOCKBACK: 0
    FIRE_ASPECT: 0
    THORNS: 0
    ARROW_FIRE: 1
    ARROW_DAMAGE: 4
potion_limits:
    STRENGTH: 0
    WEAKNESS: 0
    SLOWNESS: 0
    INVISIBILITY: 0
    POISON: 0
    
border_sizes:
    NORMAL: 2000
    NETHER: 1000
    THE_END: 1500
diamond_ore_alerts: true

subclaim_name_characters_min: 3
subclaim_name_characters_max: 16

faction_name_characters_min: 3
faction_name_characters_max: 16
max_members_per_faction: 25

road_min_height: 0
road_max_height: 256

end_portal_radius: 20
end_portal_center: 500

#milliseconds, default 1hour
default_deathban_duration: 3600000

teammate_colour: "GREEN"
ally_colour: "GOLD"
enemy_colour: "RED"

safezone_colour: "GREEN"
road_colour: "GOLD"
warzone_colour: "DARK_RED"
wilderness_colour: "DARK_GREEN"
max_allies_per_faction: 1
max_claims_per_faction: 8
allow_claiming_besides_roads: true

dtr_millis_between_updates: 45000

dtr_increment_between_updates: 0.1
maximum_dtr: 6.0

exp_multiplier_general: 2.0
exp_multiplier_fishing: 2.0
exp_multiplier_smelting: 2.0
exp_multiplier_looting_per_level: 1.5
exp_multiplier_luck_per_level: 1.5
exp_multiplier_fortune_per_level: 1.5

conquest_point_loss_per_death: 20
conquest_required_win_points: 300

found_diamonds_alerts: true
combat_log_despawn_ticks: 600
combat_log_prevention_enabled: true



