![2024-02-25 19_24_02-KLCiS Voucher System - Voucher Store](https://github.com/darkhoundz/KLCiS-QR-API/assets/28075740/57b81fad-42a0-42ef-931c-edae3077f388)

![2024-02-25 19_24_13-store html - KLCiS - Visual Studio Code](https://github.com/darkhoundz/KLCiS-QR-API/assets/28075740/fbefc400-91aa-4fa3-bb2c-5b02d7fb6a17)

Instruction:
1. Download and extract the repository.
2. Exit the store.html, find this line: PUT_YOUR_KLCIS_API_KEY_HERE and replace the value with your KLCiS API Key
3. Find these code:

             <select id="amountDropdown" name="amount" class="form-select text-success text-lg btn-block">
                    <!--PAKI-EDIT NG VALUE SAKA DESCRIPTION BASE SA VOUCHER AMOUNT NA NAKA-UPLOAD SA IYONG KLCIS ACCOUNT -->
                          <option value="11">₱11.00 - PROMO! 1 DAY UNLI (no pause)</option>
                              <option value="5">₱5.00 - 3 HOURS (no exp.|unli pause)</option>
                              <option value="10">₱10.00 - 7 HOURS (no exp.|unli pause)</option>
                              <option value="20">₱20.00 - 1 day (no exp.|unli pause)</option>
                              <option value="50">₱50.00 - 3 DAYS INTERNET</option>
                              <option value="100">₱100.00 - 7 DAYS INTERNET</option>
                            <option value="180">₱180.00 - 15 DAYS INTERNET</option>
                            <option value="300">₱300.00 - 30 DAYS INTERNET</option>
                      </select>

6. Replace the value and description according to the price of the voucher you hav uploaded in the KLCiS Admin Dashboard

Application:

You can host this online/offline, or add this to your Mikrotik, Omada and AdopiSoft system.
For other software, kindly wait for the updates.
