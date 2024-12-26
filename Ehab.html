const Dashboard = () => {
  // Parse and prepare the data
  const rawData = `Time Population(millions)Traffic Numbers(millions/day)Public TransportVehicles(thousands)Metro VehiclesVehicleOwnership(millions)Ride-SharingFleet (thousands)GDP Growth Rate(%)Average FuelPrice (EGP/Liter)EVs Share ofFleet (%)Public Transport Vehicles per Capita(actual)Public Transport Vehicles per Capita(MIN. Expected)`;

  // Process the data into an array of objects
  const processData = (text) => {
    const rows = text.split('\n').filter(row => row.trim());
    return rows.map(row => {
      const [
        time, 
        population, 
        traffic, 
        publicTransport, 
        metroVehicles, 
        vehicleOwnership, 
        rideSharing, 
        gdpGrowth, 
        fuelPrice, 
        evsShare, 
        ptPerCapitaActual, 
        ptPerCapitaExpected
      ] = row.split(' ').filter(cell => cell.trim());
      
      return {
        time,
        population: parseFloat(population),
        traffic: parseFloat(traffic),
        publicTransport: parseFloat(publicTransport),
        metroVehicles: parseFloat(metroVehicles),
        vehicleOwnership: parseFloat(vehicleOwnership),
        rideSharing: parseFloat(rideSharing),
        gdpGrowth: parseFloat(gdpGrowth),
        fuelPrice: parseFloat(fuelPrice),
        evsShare: parseFloat(evsShare),
        ptPerCapitaActual: parseFloat(ptPerCapitaActual),
        ptPerCapitaExpected: parseFloat(ptPerCapitaExpected)
      };
    });
  };

  const data = processData(rawData);

  return (
    <div className="p-4 space-y-6">
      <h1 className="text-2xl font-bold mb-6">Transport Metrics Dashboard</h1>
      
      <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
        {/* Traffic vs Public Transport */}
        <Card className="w-full">
          <CardHeader>
            <CardTitle>Traffic Numbers vs Public Transport Vehicles</CardTitle>
          </CardHeader>
          <CardContent>
            <div className="h-64">
              <ResponsiveContainer width="100%" height="100%">
                <LineChart data={data}>
                  <CartesianGrid strokeDasharray="3 3" />
                  <XAxis dataKey="time" angle={-45} textAnchor="end" height={60} />
                  <YAxis yAxisId="left" />
                  <YAxis yAxisId="right" orientation="right" />
                  <Tooltip />
                  <Legend />
                  <Line yAxisId="left" type="monotone" dataKey="traffic" stroke="#8884d8" name="Traffic (M/day)" />
                  <Line yAxisId="right" type="monotone" dataKey="publicTransport" stroke="#82ca9d" name="Public Transport (K)" />
                </LineChart>
              </ResponsiveContainer>
            </div>
          </CardContent>
        </Card>

        {/* Vehicle Ownership and Ride Sharing */}
        <Card className="w-full">
          <CardHeader>
            <CardTitle>Vehicle Ownership vs Ride Sharing Fleet</CardTitle>
          </CardHeader>
          <CardContent>
            <div className="h-64">
              <ResponsiveContainer width="100%" height="100%">
                <LineChart data={data}>
                  <CartesianGrid strokeDasharray="3 3" />
                  <XAxis dataKey="time" angle={-45} textAnchor="end" height={60} />
                  <YAxis yAxisId="left" />
                  <YAxis yAxisId="right" orientation="right" />
                  <Tooltip />
                  <Legend />
                  <Line yAxisId="left" type="monotone" dataKey="vehicleOwnership" stroke="#ff7300" name="Vehicle Ownership (M)" />
                  <Line yAxisId="right" type="monotone" dataKey="rideSharing" stroke="#00c49f" name="Ride Sharing Fleet (K)" />
                </LineChart>
              </ResponsiveContainer>
            </div>
          </CardContent>
        </Card>

        {/* EVs Share and Fuel Price */}
        <Card className="w-full">
          <CardHeader>
            <CardTitle>EVs Share vs Fuel Price</CardTitle>
          </CardHeader>
          <CardContent>
            <div className="h-64">
              <ResponsiveContainer width="100%" height="100%">
                <LineChart data={data}>
                  <CartesianGrid strokeDasharray="3 3" />
                  <XAxis dataKey="time" angle={-45} textAnchor="end" height={60} />
                  <YAxis yAxisId="left" />
                  <YAxis yAxisId="right" orientation="right" />
                  <Tooltip />
                  <Legend />
                  <Line yAxisId="left" type="monotone" dataKey="evsShare" stroke="#8884d8" name="EVs Share (%)" />
                  <Line yAxisId="right" type="monotone" dataKey="fuelPrice" stroke="#82ca9d" name="Fuel Price (EGP/L)" />
                </LineChart>
              </ResponsiveContainer>
            </div>
          </CardContent>
        </Card>

        {/* Public Transport per Capita */}
        <Card className="w-full">
          <CardHeader>
            <CardTitle>Public Transport per Capita: Actual vs Expected</CardTitle>
          </CardHeader>
          <CardContent>
            <div className="h-64">
              <ResponsiveContainer width="100%" height="100%">
                <LineChart data={data}>
                  <CartesianGrid strokeDasharray="3 3" />
                  <XAxis dataKey="time" angle={-45} textAnchor="end" height={60} />
                  <YAxis />
                  <Tooltip />
                  <Legend />
                  <Line type="monotone" dataKey="ptPerCapitaActual" stroke="#8884d8" name="Actual" />
                  <Line type="monotone" dataKey="ptPerCapitaExpected" stroke="#82ca9d" name="Expected" />
                </LineChart>
              </ResponsiveContainer>
            </div>
          </CardContent>
        </Card>
      </div>
    </div>
  );
};

