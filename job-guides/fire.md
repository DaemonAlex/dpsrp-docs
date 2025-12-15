# Fire Department Guide

Complete guide to firefighting on DPSRP.

## Overview

DPSRP uses **London Studios SmartFires** - a comprehensive fire system with realistic fire types, automatic spawning, spreading mechanics, and dispatch integration.

## Getting Started

### Requirements
- Apply to Fire Department
- Complete fire academy training
- Clean background

### Fire Stations
- Los Santos Fire Department (LSFD)
- Paleto Bay Station
- Sandy Shores Station

## Fire Types

Different fires require different approaches:

| Type | Characteristics | Extinguish With |
|------|-----------------|-----------------|
| Normal | Standard fire | Water, Extinguisher, Foam |
| Electrical | Sparking, dangerous | Extinguisher, Foam ONLY |
| Chemical | Intense, spreading | Extinguisher, Foam ONLY |
| Bonfire | Large flames | Water, Extinguisher, Foam |

**WARNING:** Using water on electrical or chemical fires makes them WORSE!

## Equipment

### Extinguishing Tools
| Tool | Best For |
|------|----------|
| Fire Hose (weapon_hose) | Large fires, water-safe |
| Fire Extinguisher | All fire types |
| Foam Mode | Electrical/Chemical fires |

### Hose Controls (Smart Hose V2)
- Equip hose from fire truck
- Aim and spray at fire base
- Toggle foam mode with `/foam` command

### Fire Trucks (SmartVehicle)

London Studios SmartVehicle provides advanced controls for fire apparatus including ladder trucks, tiller trucks, and aerial platforms.

**Setup Commands:**
| Command | Description |
|---------|-------------|
| `/setupvehicle` | Initialize smart vehicle features |
| `/setupvehicle [type]` | Setup with specific ladder type (if vehicle supports multiple) |
| `/resetvehicle` | Reset vehicle to default state |
| `/entercage` | Enter aerial cage/bucket (within 20m of vehicle) |
| `/exitcage` | Exit aerial cage |

**Vehicle Types:**
| Type | Description |
|------|-------------|
| American Rearmount Ladder | Traditional rear-mounted aerial ladder |
| Tiller Ladder Truck | Dual-driver aerial with rear steering |
| Standard Engine | Basic fire engine with equipment |

**Controls:**
| Key | Action |
|-----|--------|
| E | Dynamic attachment control (interact with vehicle components) |
| Prompt appears | Approach vehicle within 4m to see control prompt |

**Cage/Bucket Operations:**
- Enter cage from within 20m of the vehicle
- Used for elevated rescue and firefighting
- Control aerial platform movement from inside cage
- Exit returns you to ground level

**Features:**
- Automatic setup when entering vehicle
- Realistic ladder extension and rotation
- Aerial platform positioning
- Deck guns (water monitors)
- Equipment compartment access
- Sound effects for hydraulics

## Responding to Fires

### Dispatch Alerts
When a fire starts, you'll receive:
- Notification alert
- Blip on map
- Route to location
- Fire type information

### Fire Response Procedure
1. Accept dispatch call
2. Don firefighting gear
3. Drive to scene (Code 3)
4. Assess fire type and size
5. Select appropriate equipment
6. Attack fire at the base
7. Monitor for spreading
8. Declare scene clear

### Fire Assessment
| Factor | Check For |
|--------|-----------|
| Type | Electrical box? Chemical containers? |
| Size | Number of flames |
| Spread Risk | Nearby structures/vegetation |
| Victims | Anyone trapped? |

## Automatic Fires

The server spawns fires automatically:
- Based on number of firefighters on duty
- Random locations (city, Sandy, Paleto)
- Various types and sizes
- Fires can spread if not contained

### Fire Locations
| Area | Description |
|------|-------------|
| City | Urban fires, electrical, dumpsters |
| Sandy | Desert area, trailer parks, generators |
| Paleto | Rural, sawmill, farms, lodges |

## Fire Behavior

### Spreading
- Fires spread every ~2 minutes
- Spread distance configurable
- Contain quickly to prevent spread

### Smoke
- Fires produce smoke
- Smoke persists after fire is out
- Different smoke types per fire

### Auto-Extinguish
- Fires auto-remove after 10 minutes if unattended
- Don't rely on this - respond promptly!

## Commands

### Fire Management
| Command | Description |
|---------|-------------|
| `/lighter` | Start small fire (training/arson RP) |
| `/startfire [type] [size]` | Start manual fire |
| `/stopfire` | Stop nearest fire |
| `/stopallfires` | Stop all fires (admin) |
| `/startsmoke` | Start smoke effect |
| `/stopsmoke` | Stop smoke |
| `/foam` | Toggle foam mode on hose |

### Automatic Fire Control
| Command | Description |
|---------|-------------|
| `/toggleautofires` | Enable/disable auto fires |
| `/triggerautofire` | Force spawn automatic fire |
| `/setfiresaop` | Set area of patrol |
| `/togglefiresaop` | Toggle all patrol areas |

## Deck Guns & Water Monitors

Fire trucks with deck guns:
- Mounted water cannons
- High-volume output
- Effective for large fires
- Controlled from vehicle

## Society Payments

Firefighters earn money per fire:
- $3,000 - $7,000 per fire extinguished
- Paid to fire department society
- Distributed by department leadership

## Safety Procedures

### Scene Safety
1. Assess hazards before approaching
2. Wear proper PPE
3. Establish safe perimeter
4. Watch for structural collapse
5. Monitor for flashover/backdraft

### Electrical Fires
- Do NOT use water
- Use extinguisher or foam only
- Cut power if possible
- Keep distance from sparking

### Chemical Fires
- Do NOT use water
- Foam or extinguisher only
- Evacuate civilians
- Request hazmat if needed

## Coordination

### With Police
- Scene security
- Traffic control
- Investigation (arson)

### With EMS
- Medical standby
- Victim treatment
- Rehabilitation

## Ranks

| Grade | Title |
|-------|-------|
| 0 | Probationary Firefighter |
| 1 | Firefighter |
| 2 | Senior Firefighter |
| 3 | Engineer |
| 4 | Lieutenant |
| 5 | Captain |
| 6 | Battalion Chief |
| 7 | Fire Chief |

## Tips for Success

1. **Know your fire types** - Wrong equipment makes it worse
2. **Attack the base** - Aim at bottom of flames
3. **Work as a team** - Large fires need multiple units
4. **Communicate** - Radio updates to dispatch
5. **Stay safe** - Don't become a victim
6. **Practice** - Use training fires regularly
7. **Monitor spread** - Contain before it grows
