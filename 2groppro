def main():
    inventory = [["item1", 10], ["item2", 20], ["item3", 30]]
    while True:
        printMenu()
        choice = input("Enter your choice: ")
        if choice.lower() == "p":
            printInventory(inventory)
        elif choice.lower() == "a":
            addItem(inventory)
        elif choice.lower() == "s":
            sortInventory(inventory)
        elif choice.lower() == "x":
            print("Exiting program...")
            break
        else:
            print("Invalid choice. Please try again.")

def printMenu():
    print("*" * 47)
    print("*" + " " * 45 + "*")
    print("*" + " " * 16 + "INVENTORY MANAGEMENT" + " " * 16 + "*")
    print("*" + " " * 45 + "*")
    print("*" + " " * 3 + "(P)rint Inventory" + " " * 23 + "*" + " " * 3)
    print("*" + " " * 3 + "(A)dd Item to Inventory" + " " * 18 + "*" + " " * 3)
    print("*" + " " * 3 + "(S)ort Inventory by Category" + " " * 15 + "*" + " " * 3)
    print("*" + " " * 3 + "E(X)it Program" + " " * 27 + "*" + " " * 3)
    print("*" + " " * 45 + "*")
    print("*" * 47)

def printInventory(inventory):
    print("Current inventory:")
    for item in inventory:
        print(f"{item[0]}: {item[1]}")

def addItem(inventory):
    item = input("Enter item name: ")
    quantity = int(input("Enter quantity: "))
    inventory.append([item, quantity])
    print(f"{quantity} {item}(s) added to inventory.")

def sortInventory(inventory):
    inventory.sort(key=lambda x: x[0])
    print("Inventory sorted by category.")

if __name__ == "__main__":
    main()
