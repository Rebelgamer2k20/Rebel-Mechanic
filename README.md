# Rebel-Mechanic
mechanic script for qbcore
# Rebel Mechanic Script


## Description
`Rebel_mechanic` is a comprehensive mechanic script for the QB-Core framework that adds vehicle modifications, lift interactions, an oil change system, car key management, and society account integration.

## Features
- **Vehicle Lifts**: Interact with vehicle lifts to repair vehicles.
- **Oil Changes**: Require oil changes after a certain mileage and manage oil life. Vehicles stop functioning at 25% oil life.
- **Material Management**: Use metal, copper, and aluminum to build vehicle parts.
- **Car Key Management**: Change and duplicate car keys.
- **Mechanic Job**: Fully integrated mechanic job with customizable grades and permissions for Police and EMS.
- **Vehicle Garage**: Store vehicles in the mechanic's garage.
- **Checkout Location**: Process payments using `qb-banking`.
- **Society Account**: Manage a society account for the mechanic job using `qb-banking`.

## Installation

1. **SQL Setup**:
    - Import the `rebel_mechanic.sql` file into your database.

2. **Resource Setup**:
    - Place the `Rebel_mechanic` folder into your `resources` directory.
    - Add `ensure Rebel_mechanic` to your `server.cfg`.

3. **Dependencies**:
    - Ensure you have `qb-core`, `qb-target`, and `qb-banking` resources running on your server.

4. **Configuration**:
    - Customize the settings in the `config.lua` file, including lift locations, checkout locations, and material requirements.

5. **Commands**

- **/duplicatekey**: Duplicate the car key for the vehicle you are in.
- **/changeoil**: Manually change your vehicle's oil.
- **/scancar**: Scan the vehicle for damage and oil status.

## Future Updates
- Extend functionality with additional vehicle services.
- Add more customization options in the config.

## Credits
- Developed by Rebel Deveopement].
- Special thanks to the QB-Core and FiveM communities.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
