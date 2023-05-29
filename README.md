# Design-parking-system-Leetcode
class ParkingSystem { public: map&lt;int,int> mp;     ParkingSystem(int big, int medium, int small) {      mp[1] = big;      mp[2] = medium;      mp[3] = small;      }          bool addCar(int carType) {          if(mp[carType]>0){ mp[carType]--; return true;          }         else{             return false;         }      } };
