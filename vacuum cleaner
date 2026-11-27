def vacuum_agent():
    
    room_A = input("Enter status of Room A (Clean/Dirty): ").lower()
    room_B = input("Enter status of Room B (Clean/Dirty): ").lower()
    location = input("Enter vacuum location (A/B): ").upper()

    print("\nVacuum Cleaner Agent Actions:")

    if location == "A":
        if room_A == "dirty":
            print("Room A is Dirty -> Cleaning Room A")
            room_A = "clean"
        else:
            print("Room A is Clean -> Moving to Room B")

        location = "B"

        if room_B == "dirty":
            print("Room B is Dirty -> Cleaning Room B")
            room_B = "clean"
        else:
            print("Room B is already Clean")

    elif location == "B":
        if room_B == "dirty":
            print("Room B is Dirty -> Cleaning Room B")
            room_B = "clean"
        else:
            print("Room B is Clean -> Moving to Room A")

        location = "A"

        if room_A == "dirty":
            print("Room A is Dirty -> Cleaning Room A")
            room_A = "clean"
        else:
            print("Room A is already Clean")

    else:
        print("Invalid location!")

    print("\nFinal Status:")
    print("Room A:", room_A.capitalize())
    print("Room B:", room_B.capitalize())


vacuum_agent()
